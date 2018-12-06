# deseq
workflow for deseq from countdata 

This workflow was created to perform a differential gene expression analysis using count data from RNA sequencing. For the most part, the code shares similarities with deseq vignette from bioconductor. This summarized version contains a few alternative ways to make plots for instance making volcano plot, or tsne plot.

Bioclite source should be used to install deseq2 and biomart and update all to make sure the analysis runs smoothly. At times, a few components, if said missing, may need to individually be installed.

Care should be taken during count data preparation to ensure heading and rownames from first column are defined appropriately during import.

Kegg pathway analysis part at the end of the script is still a work in progress.
