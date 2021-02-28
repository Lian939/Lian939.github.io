---
title: Article summary V
---

## Summary
The bootstrap, introduced by [Bradley Efron (1979)](https://www.jstor.org/stable/2958830?seq=5#metadata_info_tab_contents), is a nonparametric way of estimating standard errors by resampling the data. [Freedman and Peters (1984)](https://www.jstor.org/stable/2288341?seq=1#metadata_info_tab_contents) applied, for the first time, bootstrap to generalized least squares. This article compared the performance of conventional asymptotic estimates of standard error to the performance of a bootstrap procedure in the setting of a single econometric equation. The main finding was that for generalized least squares with estimated covariance matrices, the asymptotic formulas for standard errors could be too optimistic, sometimes by quite large factors even considering a model with normal errors. By using the Regional Demand Forecasting Model (RDFOR), it seems like the bias in the conventional asymptotics was not due to the autoregressive structure and the discreteness of the error distribution. Compared with asymptotic formulas, the bootstrap was distribution-free and developed the appropriate finite-sample behavior for the estimates. And the developments in the estimation of seemingly unrelated regressions, proposed by [Srivastava and Dwivedi (1979)](https://www.sciencedirect.com/science/article/abs/pii/0304407679900617) were only somewhat better. Also, some mathematical results and computational details are provided in this paper.

## Reaction
The bootstrap method is a very useful statistical estimation method, and this technique involves a relatively simple procedure but repeated so many times. I couldn’t imagine that the cost for the bootstrap experiments and validation is so expensive in the 1980s. As computing power has increased and becomes less expensive, bootstrap techniques have become more widespread. The bootstrap allows us to calculate standard errors for statistics for when no formula exists and to check the normality of the sampling distribution of statistics that theory doesn’t easily handle. This paper provided a good example of the use of bootstrap in the regression context and the stability of bootstrap. Except for estimate standard errors, we can also use the bootstrap to estimate the bias of our estimation, and also to construct the confidence intervals. However, the bootstrap is not perfect. Freedman et al. thought the bootstrap was the better method for small data. But it seems like almost all the variation in a bootstrap distribution for a statistic is due to the selection of the original random sample from the population, so the bootstrap distributions based on small samples can be quite variable, the estimation may not be accurate, and inference from a small data may also be unreliable. Also, at the beginning of the paper, the author mentioned bootstrap was like Jackknife. I’m interested in the difference between them. Unlike Bootstrap, Jackknife is an iterative process. Jackknife is ten times computationally less intensive, and more conservative than bootstrapping, producing slightly larger estimated standard errors. There are many resampling methods (e.g. permutation tests, Monte Carlo methods, … see [Wikipedia](https://en.wikipedia.org/wiki/Resampling_(statistics))). It’s important to know the difference, the strength, and when to use which method. 

## Questions
1. What’s the main weakness and disadvantage of bootstrap? How to improve the biased downwards estimates? What’s the appropriate way to fix that the residuals $$\hat{\epsilon}$$ is smaller than the disturbance term $$\epsilon$$ due to the effect of fitting?
2. When to use the conventional asymptotic formulas or bootstrap?
3. How to choose different resampling methods?  











