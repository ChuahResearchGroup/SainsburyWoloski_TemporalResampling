# SainsburyWoloski_TemporalResampling

Code for the manuscript titled: "Evaluating the Effects of Temporal Downsampling on Network Structure and Pathways Enrichment in Circadian Proteomics", currently under review at the journal _Mathematical and Computational Biology_

The folder titled "UMAP Experiments" contains analyses where a baseline UMAP embedding was computed on T = 24 time points, the data was downsampled, the UMAP embedding recomputed, and then compared to the baseline UMAP embedding.


The folder titled "PCA Experiments" contains analyses where a baseline PCA model was computed on T = 24 time points, the data was downsampled, the PCA model recomputed, and then compared to the baseline PCA model.

The folder titled "Time Point Removal" contains all analyses performed by downsampling time-series data such that every _x_ time points were removed.  For instance, a T = 24 dataset was used in this study, and the structure of the data when T = 12 (or every other point removed) was compared to the T = 24 baseline.

"proteomics_collins_postlimbrecho.csv" Is the preprocessed (post-LIMBR and post-ECHO) version of the data from Collins et. al which can be found here: https://pmc.ncbi.nlm.nih.gov/articles/PMC7849412/.  The data used in this study filtered this data for BH p-value < 0.05, and removed "Overexpressed" and "Repressed" as per De Los Santos et. al's paper: https://pmc.ncbi.nlm.nih.gov/articles/PMC7523678/

