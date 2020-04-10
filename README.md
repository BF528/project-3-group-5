# Project Description
In this project we aligned rat short reads to reference genome and performed differential analysis on RNA-seq data as well as microarray expression data to compare the results from our analysis to the literature.

# Contributors

Data Curator: Evie Wan \
Programmer: Eetu Eklund \
Analyst: Salam AlAbdullatif \
Biologist: Mary T. Yohannes

# Repository Contents

Data Curator: \
STAR.qsub: star alignment script \
multiqc.qsub: multiqc report script \
multiqc_report_1.html: STAR and FASTQC output 

Programmer: \
Project_3.Rmd: reads counts reads from csv and combines them with the controls into one file \
performs DESeq2 analysis on each mode of action with the appropriate controls \
multiqc_report_1_counts.html: multiqc report output from read counts 

Analyst: 
Project_3 Rmd: limma sections determines differential gene expression for each mode of action with the appropriate controls in the microarray data. concordance section calculates and plots the concordance between the microarray and RNA-seq results

Biologist: \
Project_3.Rmd: reads in DESeq analysis results, filter data on set cutoff values to find differentially expressed genes from each treatment for DAVID analysis, and produce a heatmap-based hierarchical clustering using the heatmap() function in R
