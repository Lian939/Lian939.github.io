---
layout: post
title: Article summary IV
---

## Summary
Machine learning (ML) has been employed to develop cancer risk models for nonmelanoma skin cancer (NMSC). This study is a good example. In this study, Wang et al. used a semi-supervised ML approach to predict the likelihood of the development of NMSC by analyzing two million randomly sampled patients from the Taiwan National Health Insurance Research Database. A convolutional neural network (CNN) analyzed 3 years of clinical diagnostic information (i.e., International Classification of Diseases, Ninth Revision, Clinical Modification (ICD-9-CM) diagnosis and procedure codes and prescriptions) and temporal- sequential information (i.e., dates of clinical visits and days of prescriptions) to predict the development of NMSC of a given patient within the next year and achieved an area under the receiver operating characteristic curve (AUROC) of 0.89, with a mean (SD) sensitivity of 83.1% (3.5%) and mean (SD) specificity of 82.3%(4.1%). This predictive analytic model may help health care professionals to target high-risk populations and optimize prevention strategies.

## Reaction
In my view, capturing the time sequentiality of clinical visits, diagnoses, and medications is very important and useful, because medical events evolved over time in the real world. Also, this study showed using CNN on electronic medical records (EMRs) data for cancer prediction appeared to be effective. Modelling on EMRs data using ML approach is useful to inform population-level interventions. However, there are some considerations and limitations for the development of this model. For example, ML is prone to the maxim "garbage in, garbage out." This maxim indicates that the quality of the dataset input determines the quality of the output. Therefore, if these data inputs are poorly labeled, then the algorithm's outputs will reflect these inaccuracies. Also, this study didn't include many important information, such as the types, pathologic characteristics, and staging of NMSC. Therefore, we need further investigation and validation, and to involve more dermatologists in the development and testing of ML. 

### Questions
1. What does convolution mean for non-imaging data?
2. How sequential data issues affect the model, such as different visit interval, the number of visits for each person are different and missing visits?
3. How to include the interaction information in the model?

[1] Wang HH, Wang YH, Liang CW, Li YC. Assessment of deep learning using nonimaging information and sequential medical records to develop a prediction model for nonmelanoma skin cancer. Jama Dermatology. 2019 Nov 1;155(11):1277-83.

