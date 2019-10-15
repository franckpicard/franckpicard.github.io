---
layout: page
title: Research
sidebar_link: true
---

The aim of my research is to develop statistical methods dedicated to the analysis of biological data, with an emphasis on computational biology and high throughput technologies.

### Single Cell genomics

We develop statistical methods for the analysis of single cell data. We started by proposing a new method for PLS for classification, and we recently proposed a probabilistic version of PCA adapted to the analysis of over-dispersed counts with zero inflation. Recent developments focus on ATACSeq data analysis.

You can check the page of the [SingleStatomics](http://anr-singlestatomics.pages.math.cnrs.fr/) project


### Point process modeling in genomics

Recent projects focus on the spatial modeling of genomic data using point processes. We developed a testing procedure based on continuous testing to compare maps of genomic features, while controling for multiple (continuous) error rates. We also develop Hawkes models to catch spatial interactions between genomic features.

### Replication origins in vertebrates

We work on the spatial program of replication at fine scales in vertebrate genomes. We characterized replication origins in humans by analyzing Oriseq data, and we determined epigenetic signatures that characterize the spatio temporal program of replication. Our method of peak detection using scan statistics can be reproduced using <a href="{{ '/assets/soft/scan-method.zip' | prepend: site.baseurl | prepend: site.url }}">this code</a> (with a toy example). We are currently working on the conservations of replication origins in vertebrates, and on the better characterization of these epigenomic signatures, especially with ATACSeq data.


### Functional Data analysis

We developed curve clustering models that account for an inter-individual variability throught mixed functional models. We also developed a shrinkage method for functional mixed models. More recent developments concern functional models in the Poisson case (functional regression and PCA).


### Population Genomics and sex-linked genes

We developed a statistical approach to infer sex-linked genes based on a controlled cross. This method is available with the sexdetector software and we are currently developing a population-based model to enrich this method.

