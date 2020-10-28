---
title: Article summary VIII
---

## Summary
Pearl introduced empirical researchers to the latest developments in causal inference and emphasized the paradigmatic shift that must be carried out when moving from traditional statistical analysis to multivariate data causal analysis. This review presented the assumptions that underly all causal inferences, the languages used in formulating those assumptions, the conditional nature of all causal and counterfactual claims, and the methods that have been developed for the assessment of such claims. This paper surveyed recent advances in causal analysis from the unifying perspective of the structural theory of causation (SCM) and showed how statistical methods can be supplemented with the needed ingredients. SCM combined features of the structural equation models (SEM), the potential-outcome framework and the graphical models. SCM overcame mental barriers by offering a friendly mathematical machinery for cause-effect analysis and a formal foundation for counterfactual analysis and offered statistical investigators a powerful and comprehensive methodology for empirical research. 

## Reaction
This paper illustrated using a general theory of causation based on SCM, which is based on encoding causal assumptions in the language of diagrams, translating these assumptions into counterfactual notation, performing the mathematics in the algebraic language of counterfactuals and, finally, interpreting the result in graphical terms or plain causal language. It’s very interesting to say that causal assumptions are encoded not in the links but, rather, in the missing links in path diagrams. It’s important to point out the two assumptions of the identifiable controlled distribution function. If it’s identifiable, the controlled (post-intervention) distribution can be estimated from data governed by the pre-intervention distribution. Moreover, the covariate selection is noteworthy. The risk difference in each stratum of admissible set S gave the correct causal effect in that stratum. With the back-door criterion, causality could remove any “confounding” from its store of enigmatic and controversial concepts. However, we only can estimate the causal effects when there existed set of variables that is sufficient for adjustment. Also, I agreed that propensity score methods cannot be expected to reduce bias in case the set S does not satisfy the back-door criterion. Some covariates may actually increase bias if included in the analysis using propensity score methods. 

### Questions
1. What are do-free expressions? Why can only do-free expressions be estimated from non-experimental data (p116)? 
2. If the treatment variable may take only a finite number of values, the combination of these two assumptions yields testable implications, and these can be used to alert investigators to possible violations of two assumptions in the model of Fig. 5(a) (p125)? What does this mean?
3. What’s the conditional ignorability (p128)? 
4. What’s the difference between evaluating the “effects of causes” and “causes of effects”?
5. Why is potential-outcome approach called black-box approach?


[1] Pearl J. Causal inference in statistics: An overview. Statistics surveys. 2009; 3:96-146.
