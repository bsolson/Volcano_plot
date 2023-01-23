# Volcano_plot
Quick and dirty volcano plot for RNAseq data. Python with Jupyter notebook.

This is a quick and dirty python script to create volcano plots from RNA-sequencing data. 
It is not very elegant code and was primarily used as a learning exercise to teach myself python, matplotlib, numpy, etc.
Better code is available (EnhancedVolcano for R), however, this code works fine.
This code is being uploaded to GitHub as it was used to form some volcano plot figures in Russell et al. 2023.

The code simply reads in a tab-delimited .txt file of DESeq2 result outputs comparing two groups and plots the p-adjusted value along the log2fold change.
It requires some manual manipulation for color, size, shape, and label location, but works. 
