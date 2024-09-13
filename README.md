# Bioinformatic Resorces Project (2024)

This repository contains the code and workflow used for RNA-seq differential expression analysis from TCGA cancer datasets. The project involves analyzing RNA-seq counts from tumor and control samples to identify differentially expressed genes and explore their biological significance.

Main Steps:

	1.	Data Preprocessing:
	  •	Loaded RNA-seq counts and annotations.
	  •	Filtered protein-coding genes using the biomaRt package.
	2.	Differential Expression Analysis:
	  •	Performed using edgeR to detect up- and down-regulated genes based on strict cutoffs (adjusted p-value < 0.01, logFC > 1.5).
	  •	Visualized results with a volcano plot and heatmap.
	3.	Gene Set Enrichment Analysis:
	  •	Analyzed top enriched GO terms and pathways using clusterProfiler.
	4.	Pathway Visualization:
	  •	Generated pathway visualizations using pathview.
	5.	Transcription Factor Analysis:
	  •	Identified enriched transcription factors in promoters of differentially expressed genes.
	6.	Protein-Protein Interaction Network:
	  •	Used STRING and igraph to construct and analyze interaction networks among the identified genes.

This repository includes all scripts needed to replicate the analysis, following the workflow developed during the course.
