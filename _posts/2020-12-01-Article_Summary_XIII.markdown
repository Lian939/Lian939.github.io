---
title: Article summary XIII
---

## Summary
In the paper: “[Statistical Modeling: The Two Cultures](https://projecteuclid.org/download/pdf_1/euclid.ss/1009213726)”, Leo Breiman, the creator of the random forest algorithm, describes two contrasting approaches to modeling in statistics. One culture is data modeling culture, which assumes a stochastic process that produced the data. This culture is associated with traditional statistics. The other culture is called algorithmic modeling culture, which can be reduced to optimization of a loss function with an algorithm. This culture is associated with Machine Learning (ML). Much of this article is devoted to explaining the algorithmic modeling culture to statisticians unfamiliar with algorithms. He begins by describing two projects he worked on when he was a consultant. Both of these projects are described in detail and are very common machine learning projects. After that, he focus on published theoretical research in statistics at that time. Then he explains how the lack of care ensuring that models is a good substitute for reality leads statisticians to questionable conclusions drawn from models with conclusions about wrong modeling problems. Following that he discuss how the commitment to data modeling has prevented statisticians from entering new scientific and commercial fields where the data being gathered is not suitable for analysis by data models. He then describes how practitioners of machine learning do things, and then goes on to discuss the problems of multiplicity of good models, the limitations of Occam's razor of simplicity vs. accuracy, the curse of dimensionality. At last, he shows the algorithmic model can produce more and more reliable information, which arouses interest among statisticians in the algorithmic modelling community.

## Reaction
In this paper, Breiman try to persuade statisticians to stop relying solely on data modeling (which can lead to “misleading conclusions” and “irrelevant theories”) and to use algorithmic modeling to solve new real-world problems arising from large data sets. But it’s not easy. The comments on Breiman’s paper by David Cox and Bradley Efron criticized the limitation of algorithmic modeling on prediction. The difference between these two cultures still exists today. ML sounds like it’s young, vibrant, interesting to learn, and growing; Stats does not. The majority of the ML theory assumes a population or generative process creating your data. Stats wants to learn about that process, while ML wants to make predictions from observations from the process (data). There is a trade-off between interpretability and predictive accuracy: the models that are good in prediction are often complex and models that are easy to interpret are often bad predictors. I agree the ML is very useful, but I could not agree that the first concern is the accuracy of the model, only after the establishment of a high-performance model is it considered to explain it, and a highly complex, accurate model that cannot be fully explained is more valuable than a simple linear model that we fully understand and has no prediction accuracy. However, with the development of the two cultures, I believe we will find a solution to merge the advantage of the two cultures.

## Questions
1. How should we use the word “interpretable”? How could we balance the simple, interpretable functions and accuration?
2. Do we now have an updated figure for 2%/98% of statisticians who follow these two cultures?
3. Could these two different cultures fit together? Is it possible to build a data analysis framework that combines the best ideas of the two cultures?





