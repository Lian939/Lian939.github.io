---
layout: post
title: Article summary VII
---

## Summary
Rosenbaum and Rubin suggested the use of so-called balancing scores b(X), i.e. functions of the relevant observed covariates X such that the conditional distribution of X given b(X) is independent of assignment into treatment and could reduce the dimensionality of the matching problem. One possible balancing score is the propensity score, i.e. the conditional probability of receiving treatment given a set of covariates X. They demonstrated that matching on the propensity (balancing) score is equivalent to matching on the individual explanatory variables that determine the outcome variable. In this paper, they showed that easily obtained estimates of balancing scores behave like balancing scores. They also showed that if  treatment assignment is strongly ignorable  given X, then the difference between treatment and control means at each value of a balancing  score is an unbiased estimate of the treatment effect at that value, and consequently pair matching, subclassification and covariance adjustment on a balancing score can produce unbiased estimates  of the average treatment effect. Moreover they saw that common methods of multivariate adjustment in observational studies implicitly adjust for an estimated scalar balancing score.

## Reaction
Ideally, treated and control units would be exactly matched on all covariates X, so that the sample distributions of X in the two groups would be identical. Rosenbaum and Rubin showed that it is sufficient to match exactly on any balancing score b(X) to obtain the same probability distributions of X for treated and control units in matched samples. This method could control observed bias and estimate treatment effects in a wide range of research applications. However, this matching method is not robust against “hidden bias” arising from unobserved variables that simultaneously affect assignment to treatment and the outcome variable. This method doesn’t require functional form or specification assumptions in estimating treatment effects. However, the primary assumption of matching estimators is the conditional independence assumption. This requires that the value of the outcome variable is independent of treatment state, given the values of some observable variables. Any systematic treatment effect is assumed to be due to observable variables. The idea of stratification matching is to partition the common support of the propensity score into a set of strata and to calculate the impact within each strata by taking the mean difference in outcomes between treated and control observations. But how many strata should be used might be a problem. 

### Questions
1. How could we test the conditional independence assumption?
2. How might we address unobserved heterogeneity? How could we know that any differences in unobservable characteristics are random? 
3. If those individuals that fall outside the region of common support have to be disregarded, the estimate is only consistent for the subpopulation within the common support. What should we do? 
4. How should we assess the matching quality?

[1] Rosenbaum PR, Rubin DB. The central role of the propensity score in observational studies for causal effects. Biometrika. 1983 Apr 1; 70(1): 41-55.
