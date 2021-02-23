---
title: Article summary IV
---

## Summary
[Eklund et al.](https://www.pnas.org/content/113/28/7900) used large scale experimental data rather than simulated data to test the validity of statistical methods for functional magnetic resonance imaging (fMRI) data analysis for the first time. The authors used resting-state data to compare familywise error rates for voxel-based and cluster-based inferences for three fMRI statistical analysis packages (AFNI, FSL, and SPM), as well as a nonparametric permutation method. They found that, for a target familywise error rate of 5%, the parametric methods gave invalid cluster-based inferences and conservative voxel-based inferences. Non-parametric permutation tests seemed most reliable and usually controlled type I errors at the expected 5% rate. Their results suggested that the principal cause of the invalid cluster inferences is spatial autocorrelation functions that do not follow the assumed Gaussian shape. They also found a too high threshold (i.e. cluster-defining threshold (CDT) of p=0.01) leads to unacceptably high false positive rates, and the same threshold (i.e. CDT of p=0.001) in combination with cluster-extent estimation gives much better results, though still slightly biased (0.6-0.9). Given these results, they concluded that statistical methods for fMRI data analysis should be validated.

## Reaction
In this PNAS paper, Eklund and colleagues studied how reliably different correction procedures widely used in fMRI research control for multiple testing. This was an important investigation at the core of fMRI analyses. The fMRI data are images of the brain, and each image contains many thousand voxels. When we do multiple tests for every voxel, it can easily end up with 100,000 tests or more. Usually, we call a difference or an effect significant if the p value is below a pre-defined threshold 0.5. However, when we do more than one test, these 5% of false positives won’t be hold. The same issue persists when we do multiple tests for brain regions Therefore, an appropriate correction procedure to control for multiple testing is necessary and important to avoid that type I error inflates massively. Eklund et al. reported that for some techniques, multiple testing correction does not guarantee the 5% false positive rate but leads to much higher rates. Another interesting finding was that the null distribution for fMRI data partly violate the assumptions. This issue certainly contributed to the high error rates. The findings of Eklund and colleagues are important. When conducting fMRI data analysis, we should pay more attention to the assumptions. Also as mentioned in the paper, “no analysis method is perfect, and new problems and limitations will be certainly found in the future”, data and code sharing will play a key role in this. 

## Questions
1. What’s the difference between the parametric cluster-extent and non-parametric permutation test? From now on, should we only use permutation testing?
2. What should we do to avoid that the false positive rate inflates massively beyond the 5%?
3. What else can be learned to improve fMRI research?










