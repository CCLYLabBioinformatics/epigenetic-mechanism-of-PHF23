# Epigenetic-mechanism-of-PHF23
An epigenetic mechanism underlying chromosome 17p deletion-driven tumorigenesis

![image-20200801213329580](README.assets/image-20200801213329580.png)

# Citation

Our paper has been published on [Cancer Discovery](https://cancerdiscovery.aacrjournals.org/content/early/2020/12/18/2159-8290.CD-20-0336?versioned=true) 

And you could download the .pdf file for reading by clicking [here](MS/)

The supplemental data and information could be accessible by clicking [here](supplemental/)

You could downloaded raw data from [GEO Database GSE145190](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE145190)

## Overview of submitted data

Our data in this paper included two part of them, RNA-seq and ChIp-seq. And we submitted all the scripts and some important processed files to documents respectively. 

## 1. ```RNAseq``` documents

In ```RNAseq``` documents, there were tables for storing TPM, DGEs and others omics information produced in three specific experiment conditions including, pre-B, tumor and treatment parts. Besides, the expression levels of ```PHF23``` in TCGA-DLBCL were isolated in an individual table. All the code of data processing, data visualization, main figure making and statistical calculation were totally recorded in ``` RNAseq_script.R```.

## 2. ```Chipseq``` documents

In ```Chipseq``` documents, peaks annotation files were listed individually, including H3K4me3 peaks, H3K27ac peaks, HDAC1 peaks and PHF23 peaks. And interaction of different peaks mentioned in paper also had been list in documents. All the code of data processing, data visualization, main figure making and statistical calculation also were totally recorded in ``` Chipseq_script.R```.

