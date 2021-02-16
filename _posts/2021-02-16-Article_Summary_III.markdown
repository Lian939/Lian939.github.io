---
title: Article summary III
---

## Summary
Following the report that detailed numerous problems with the data, [Baggerly and Coombes](https://academic.oup.com/clinchem/article/57/5/688/5621016) identified the 5 things that should be supplied when articles are submitted to the journals before published, especially before starting clinical trials. They summarized the lessons about the role of transparency and how it might be achieved from Duke Case. In this paper, they discussed whether requiring code was extreme, the practical and typical issues when supplying extra information, the methods, and some tools to supply the extra information. The submission of code was not impractical. Identifying unlabeled data was difficult, even these data went through multiple levels of review. Mistakes were not rare and simple, such as unlabeled tables, mislabeled tables, and so on, and supplying extra information could avoid these basic mistakes. Except data and coding, extra documents related to regulatory should be supplied, e.g. submitting investigational device exemption (IDE) before omic signatures were used to guide therapy in clinical trials. The tools, such as Sweave, GenePattern, and Galaxy was good to document the analyses, and Gene Expression Omnibus allowed supplying raw data and metadata. Some R packages (e.g. MINiML and ArrayCube) could make maintaining the connections between clinical characteristics and assay data easier. 

## Reaction
Supplying the information that Baggerly and Coombes suggested is good for avoiding simple mistakes and reproducibility. I agree that there are positive effects if investigators know the code could be checked later, although checking code at review time is likely impractical. The reproducibility is useful for scientific advances of tomorrow and is particularly important if such data are to be used in clinical practice or trials. The researchers are responsible for conducting reproducible research, and funding agencies, academic institutions, and institutions managing scientific work, such as universities and industry, journals also need to put efforts to improve reproducibility. The Duke problem was not a one-off. In a terrific but depressing piece of research, [Grant Steen](https://pubmed.ncbi.nlm.nih.gov/22138727/) showed that between 2000 and 2010 around 80000 patients had undergone clinical trials based on incorrect research and for which papers were retracted. Improving reproducibility is noncontroversial. However, in practice, there is a lack of tools for packaging up the information, and any new requirements may be a burden on tight budgets. The development of easy-to-use and an integral part of scientists’ computational environment tools are needed to achieve better reproducibility. Also, Baggerly and Coombes mentioned “both the IRBs and NIH-style investigators who don’t understand that some of these algorithms are medical devices”. It can be seen that lack of training is also a problem. 


## Questions
1. Is it possible to check the code at review time?
2. How should the educational institutions and others include reproducibility in the classrooms?
3. What’s the best trade-off between the resources allocated to research for the discovery of new knowledge and to research for replication to confirm or repudiate previous knowledge?









