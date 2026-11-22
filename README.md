# SainsburyWoloski_TemporalResampling

Code for the manuscript titled: "Evaluating the Effects of Temporal Downsampling on Network Structure and Pathways Enrichment in Circadian Proteomics", currently under review at the journal _Mathematical and Computational Biology_

The folder titled "UMAP Experiments" contains analyses where a baseline UMAP embedding was computed on T = 24 time points, the data was downsampled, the UMAP embedding recomputed, and then compared to the baseline UMAP embedding.


The folder titled "PCA Experiments" contains analyses where a baseline PCA model was computed on T = 24 time points, the data was downsampled, the PCA model recomputed, and then compared to the baseline PCA model.

The folder titled "Time Point Removal" contains all analyses performed by downsampling time-series data such that every _x_ time points were removed.  For instance, a T = 24 dataset was used in this study, and the structure of the data when T = 12 (or every other point removed) was compared to the T = 24 baseline.

