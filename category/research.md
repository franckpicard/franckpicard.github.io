---
layout: category
title: Research
---

### Single Cell genomics

We develop machine learning methods for the analysis of single cell data. We started by proposing a new method for PLS for classification, and we proposed a probabilistic version of PCA adapted to the analysis of over-dispersed counts with zero inflation. Recent developments focus on kernel methods, non-parametric dimension reduction and spatial transcriptomics. Visit the [SingleStatomics](http://anr-singlestatomics.pages.math.cnrs.fr/) ANR project, and the [AI4scMed](https://ai4scmed.github.io) PEPR project (Santé Numérique).

### Point process modeling 

Our projects focus on the spatial modeling of genomic data using point processes. We developed a testing procedure based on continuous testing to compare maps of genomic features, while controling for multiple (continuous) error rates. We also propose to use the Hawkes models to catch spatial interactions between genomic features. A last contribution has been to propose a uniform deconvolution method to account for errors in the localization of binding event in ChIP-Seq data.

### Functional Data analysis

We developed curve clustering models that account for an inter-individual variability throught mixed functional models. We also developed a shrinkage method for functional mixed models. More recent developments concern functional models in the Poisson case and functional PCA for which we study convergence rates, and investigate the double asymptotics in the number of curves and the size of the grid.

### Replication origins in vertebrates

We work on the spatial program of replication at fine scales in vertebrate genomes. We characterized replication origins in humans by analyzing Oriseq data, and we determined epigenetic signatures that characterize the spatio temporal program of replication. Our method of peak detection using scan statistics can be reproduced using <a href="{{ '/assets/soft/scan-method.zip' | prepend: site.baseurl | prepend: site.url }}">this code</a> (with a toy example). We are currently working on the conservations of replication origins in vertebrates, and on the better characterization of these epigenomic signatures, especially with ATACSeq data.

### Population Genomics and sex-linked genes 

We developed a statistical approach to infer sex-linked genes based on a controlled cross. This method is available with the sexdetector software and we are currently developing a population-based model to enrich this method.
