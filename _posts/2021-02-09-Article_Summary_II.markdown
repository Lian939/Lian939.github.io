---
title: Article summary II
---

## Summary
[Baggerly and Coombes](https://www.jstor.org/stable/27801549?casa_token=W9hoRz0H7EgAAAAA%3APWriUWpsujybZVX68IT76KJE8ckuS3Mh0SYpw9VZh5577veCuXrrTl9O7VtYwRtb1s3UPywpBPDd6qgkrYXsIwlNFnH_BfE9MS4bIlD4albjVx0Sdg&seq=1#metadata_info_tab_contents) examined several related papers purporting to use microarray-based signatures of drug sensitivity derived from cell lines to predict patient response. The goals of this reanalysis differed slightly by study, including confirming the accuracy of the test set predictions and the identities of the genes comprising the signature, clarifying the combination rules and validate predictions for the single best-performing drug, and confirming the association between the drug named and the results provided. In this paper, the authors detailed many of the problems that they had encountered and expressed concern that patients in the clinical trials may have been put at unnecessary risk. These problems are simple mistakes, included confounding in the experimental design, the incorrect use of duplicate samples, using different combination rules, mixing up the gene labels (off-by-one errors), and mixing up the group labels (sensitive/resistant). This simplicity is often hidden by poor documentation, and these most simple errors are common. And then they discussed the steps they were taking to avoid such errors in their investigations, such as writing reports using *Sweave*, a literate programming combination of LATEX source and R code, checking for the most common types of errors, and so on. 

## Reaction
Discussions about reproducibility in scientific research have been on the rise lately. Because of the larger and larger datasets and extraordinarily complicated data analysis, there is great interest in whether certain data analyses can be reproduced, and the reproducibility is more and more important and necessary. Baggerly and Coombes discovered data they did not understand, mislabeled data and descriptions of idiosyncratic steps that they could not reproduce. They contacted the original researchers with their worries but felt that they were not being listened to.  When they applied their best understanding of the reported techniques to correctly labeled data, they obtained results no better than chance. But patients in clinical trials are currently being allocated to treatment arms based on these results with flawed data analysis. In particular, one of these flawed analyses reversed the labeling of the sensitive and resistant. What a terrible consequence! There are many lessons we could learn from this. As a researcher, we should have a clear, specific, and complete description of how the reported results were reached. Before publishing our results, we should have good communication with all collaborators and other experts in this field. After published, we should be responsible for any comments and questions in the future. Also, reproducibility cannot address the validity of scientific research, more efforts should be made. 


## Questions
1. Except for the poor documentation, what else is causing these problems mentioned in this paper?
2. What Problems could Reproducibility Solve? What else can we do to make the studies or analyses more credible?
3. How to improve the reproducibility, for funders, universities, journals, and researchers?








