

# Single-cell analysis notes


## Introduction
Current techological advances has made it possible to profile individual cells by allowing researchers to prepare sequenceing libraries from small amont of samples. Having data at single-cell resoultion is required to address questions that can not be addressed with high-throughput sequencing data. 


## Common challenges
Data generation- One of the major difficulty in single-cell analysis is the initial isolation and culture of a single cell.
Another challenge lies in processing power as you are analyzing individual cell in a population. This requires analysis from all aspects to understand the complexity of a cell population.

Analysis pitfalls- Single-cell data generally has low library sizes, high noise level and a large fraction of gene drop out events, i.e., failure to observe some genes although they are indeed expressed in a given cell, which makes it diffcilut to analyze compared to HTS RNA-seq data. 

Gene drop-out reasons:- The drops-outs could be biological when a gene is cimply not expressed in a cell. For example, genes involved in the divison of a cell are not expressed at each step of the cell cycle. The zeros can also be technical when the sequencing machine fails to sequence reads from a gene and a cell.


## Advantages and applications of single-cell analysis




# Resources
Harvard FAS scRNAseq workshop fall 2019- https://crazyhottommy.github.io/scRNA-seq-workshop-Fall-2019/index.html \
Data Camp scRNAseq- https://www.datacamp.com/courses/single-cell-rna-seq-workflows-in-r
simplesinglecell- https://bioconductor.org/packages/release/workflows/html/simpleSingleCell.html


# Tools
Seurat \
ScOrange \
Monocle \
Scater \
Scanpy

Welcome Genome Campus list of tools- https://www.singlecellbioinformatics.org/tools/?
Bioconductor packages for single-cell- http://bioconductor.org/packages/release/BiocViews.html#___SingleCell

# scRNAseq plant datasets
http://www.plantphysiol.org/content/179/4/1444 


# References
https://www.biorxiv.org/content/10.1101/739011v1.abstract?%3Fcollection= \
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5866720/ \
https://singlecell.biolab.si/ \
http://www.plantphysiol.org/content/179/4/1444 \
Bias, robustness and scalability in differential expression analysis of single-cell RNA-seq data [https://www.biorxiv.org/content/10.1101/143289v1] \
Guidelines for the experimental design of scRNA-seq studies
https://www.nature.com/articles/s41596-018-0073-y \

