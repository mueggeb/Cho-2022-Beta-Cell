# Cho-2022-Beta-Cell
Study of ciliary gene expression in public human islet transcriptomic datasets.

This project contains the code to generate Figure 4C and Figure 4D of the manuscript "Islet primary cilia motility controls insulin secretion" published in 2022 (First Author Jung Hoon Cho, Senior Author Jing W. Hughes).

In the scripts directory:
- Cho_Fig4C_BulkRNA.RMD contains the code needed to generate figure 4C, after the user has downloaded the previously published transcriptomic dataset and performed read quasi-mapping with Salmon.
- Cho_SingleCell_QC.RMD contain the code to perform initial QC and filtering on the previously published single cell RNA-seq dataset used to generated Figure 4D of the paper.
- Cho_Fig4D_SingleCell_Cluster_Heatmap.pdf is the code to to process and cluster the filtered dataset in Seurat, along with code to create the heatmap presented in Figure 4D of the paper.
