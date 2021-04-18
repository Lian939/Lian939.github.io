---
title: Article summary XII
---

## Summary
One often overlooked complication with high-throughput studies is batch effects, which occur because measurements are affected by laboratory conditions, reagent lots, and personnel differences. This becomes a major problem when batch effects are confounded with an outcome of interest and lead to incorrect conclusions. Using both published studies and their own analyses, [Leek et al.,2010](https://www.nature.com/articles/nrg2825) argued that batch effects (as well as other technical and biological artefacts) were widespread and critical to address. Then the authors described two solutions to reduce their impact on biological conclusions. One was experimental design solutions, which was careful study design. High-throughput experiments should be designed to distribute batches and other potential sources of experimental variation across biological groups. The other was statistical modelling solutions, which consisted exploratory and downstream statistical analyses two key steps. Exploratory analysis was used to identify the existence of batch effects and quantify their effect, as well as the effect of other technical artefacts in the data. Downstream statistical analyses were aimed to be adjusted to account for these unwanted effects. For downstream statistical analyses using linear models, batch effects can be modelled by direct adjustment or surrogate variables. 

## Reaction
[This paper](https://www.nature.com/articles/nrg2825) demonstrates the presence of batch effects and its impact can be severe, potentially completely compromising biological results. The batch effects are strong enough to change not only mean levels of gene expression between batches but also correlations and relative rankings between the expression of pairs of genes. In some cases, the direction of significant positive correlation between genes is completely reversed in different batches. Also, if batch effects go undetected, they can lead to substantial misallocation of resources and lack of reproducibility. The author also introduced two solutions to reduce these impacts. I agree with that “the information about changes in personnel, reagents, storage and laboratories should be recorded and passed onto data analysts”, because even in a perfectly designed study, batch will strongly influence the measured high-throughput data. However, it is not clear how to choose the statistical analysis method (removing batch effects and using surrogate variables) and then it is hard to incorporate adjustment for batch effects as a standard step in the analysis of high-throughput data analysis. In addition to these solutions, the authors also motioned the importance of close collaborations between laboratory biologists and data analysts in order to isolate the specific sources of batch effects and reduce the dependence on surrogates.

## Questions
1. How to correctly correct for batch effects?
2. What are the disadvantages of surrogate variable analysis (SVA)?
3. How can we be sure that SVA or direct adjustment eliminate the true or meaningful batches?


