# SBE 304 - Biostatistics (Fall 2020)
## **Course Project**

## Project Description
We were required to conduct a study to analyze gene expression (GE) data for the cancer type Lung Squamous Cell Carcinoma (LUSC).

There are two files for the GE data for this cancer type:
1. “lusc-rsem-fpkm-tcga-t_paired.txt”: GE data for tissues with cancer.
2. “lusc-rsem-fpkm-tcga_paired.txt” : GE data for tissues in a healthy case.

• Each row in the two files represent a gene, and the columns represent the expression level of this gene in different samples.

• Data are paired meaning that a healthy sample and a diseased sample are taken from the same subject. So, both GE files have the same number of cases with the same order.

## Analysis
### • Correlation

* We computed the correlation between the normal samples and the diseased samples for each gene.
* Ranked genes based on their correlation coefficient (CC) and reported the highest positive CC and the lowest negative CC and the names of these two genes.
* Plotted the expression levels of the above two genes.

### • Hypothesis Testing 

* Inferred the differentially expressed genes (DEGs); the genes whose expression level differ from one condition (healthy) to another (diseased).
* Applied a test statistic for the following two pairing cases:
    1. Samples are paired.
    2. Samples are independent.
* Applied the FDR multiple tests correction method.
* Reported the set of DEGs before and after the FDR correction for each of the above two pairing cases.
* Compared the two DEGs sets (paired and independent) after the FDR correction in terms of the common and distinct genes.


### Contributors
* Amira Omar [(AmiraOmar99)](https://github.com/AmiraOmar99)
* Alaa Tarek [(Lola-Tarek)](https://github.com/Lola-Tarek)
* Salma Haytham [(Salma-H)](https://github.com/Salma-H)
* Nouran Khaled [(NouranYoussef)](https://github.com/NouranYoussef)
