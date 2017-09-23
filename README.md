# genotypeTissueExpressionProject
Analyzed GTEx project data to increase understanding of gene expression patterns within various tissues and how they might relate to chemical exposures and disease occurrences generally.

Abstract:
Analyzed the Genotyoe-Tissue Expression (GTEx) project to increase understanding of the interaction between cancer-positive genes and the chemicals associated with diseases that are common in the presence of such genes. (xxxResult)
Introduction.
Aim.
Data. We used the tcga, toxicogenomics_chemicals, and toxicogenomics_diseases data sets.
Methods.
We used tcga to identify cancer-positive genes in toxicogenomics_diseases. That yields the co-ocurrent diseases (disease_name), from which we can extract the chemicals associated with the disease (inference_chemical_name).
For each such disease and associated chemical we looked at the interactions between the gene and the chemical. We did this by using the CTD Chemical Vocabulary to match the MeSH names from toxicogenomics_diseases to toxigenomics_chemicals.
Results.
Conclusions and discussion.
