# SBiP 2022: Omics data

In this folder you will find all the data you need to process and analyze the transcriptomics and proteomics sections of this course.

All the datasets are stored in the `./data/` folder, you will find 5 datasets:


- `raw_counts_transcriptomics`: raw counts from RNAseq
- `transcriptomics_design`: match sequencing samples to biological samples
- `gene_id_matching`: match different IDs for genes in *Synechocystis* genome
- `functional_categories`: functional categories for genes in *Synechocystis*' genome taken from CyanoBase
- `proteomics`: log ratios from proteomics

You will find an example on how to load the data in the Rmarkdown file in `./reports/loading_data_example.Rmd`
