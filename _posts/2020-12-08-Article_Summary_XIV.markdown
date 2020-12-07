---
title: Article summary XIV
---

## Summary
t-distributed Stochastic Neighbor Embedding (usually called t-SNE), proposed by [van der Maaten and Hinton in 2008](https://www.jmlr.org/papers/volume9/vandermaaten08a/vandermaaten08a.pdf), is an unsupervised, non-linear technique primarily used for high-dimensional data exploration and visualization. In this paper, they first outlined SNE algorithm as presented by [Hinton and Roweis (2002)](https://proceedings.neurips.cc/paper/2002/file/6150ccc6069bea6b5716254057a194ef-Paper.pdf), and pointed out there are two problems with it, the cost function is difficult to optimize and the crowding problem. To alleviate these problems, they presented this new technique t-SNE. The cost function used by t-SNE differs from the one used by SNE in two ways: (1) it uses a symmetrized version of the SNE cost function with simpler gradients that was briefly introduced by [Cook et al. (2007)](http://proceedings.mlr.press/v2/cook07a/cook07a.pdf) and (2) it uses a Student-t distribution rather than a Gaussian to compute the similarity between two points in the low-dimensional space. To evaluate t-SNE, they performed experiments on five data sets that represent a variety of application domains and compare it with many other non-parametric visualization techniques for dimensionality reduction, including Sammon mapping, Isomap, and Locally Linear Embedding. The visualizations produced by t-SNE are significantly better than those produced by the other techniques on almost all of the data sets. And then they discussed the differences between t-SNE and other non-parametric techniques. A number of weaknesses and possible improvements of t-SNE also discussed in this paper.

## Reaction
The idea behind t-SNE is that we are given a set of high dimensional vectors and want to obtain a faithful two-dimensional representation as much as this is possible. In the low-dimensional space it attracts the points that are close or similar in the high dimensional space, and repels the points that are far from each other. In this way, t-SNE maps the multi-dimensional data to a lower dimensional space and attempts to find patterns in the data by identifying observed clusters based on similarity of data points with multiple features. However, after this process, the input features are no longer identifiable, and you cannot make any inference based only on the output of t-SNE. And t-SNE does not define a function to reduce dimensionality, and has no parameters. Hence it is mainly a data exploration and visualization technique. Another problem is the non-convexity of optimization. We will get different results if we run multiple times even using various tricks. But these problems do not affect its popularity. The big advantage of t-SNE is that it can handle the crowding problem very well by using a longer tail probability distribution to spread the points out. Conducting gradient descent to optimize this distribution is great. The negative gradient - push and positive gradient - pull finally stabilize the point in low-dimensional space. And the gradient of the symmetric version of SNE is simpler, which is faster to compute.


## Questions
1. How should we set the perplexity in t-SNE?
2. What are the differences between PCA and t-SNE?
3. What’s the meaning of the cluster size (bounding box measurements) and the distance between clusters?
4. The random walks on neighborhood graphs?






