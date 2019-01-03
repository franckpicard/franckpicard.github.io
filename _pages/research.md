---
layout: page
title: Research
sidebar_link: true
---

The aim of my research is to develop statistical methods dedicated to the analysis of biological data, with an emphasis on computational biology and high throughput technologies.

# Current Projects

### Single Cell genomics

Together with [J. Mold](http://ki.se/en/cmb/jonas-frisens-group), [L. Modolo](http://www.ens-lyon.fr/LBMC/laboratoire/annuaire/modolo-laurent), [G. Durif]() and [S. Lambert-Lacroix](http://membres-timc.imag.fr/Sophie.Lambert/) we develop statistical methods for the analysis of single cell data. We started by proposing a new method for PLS for classification, and we recently proposed a probabilistic version of PCA adapted to the analysis of over-dispersed counts with zero inflation. Recent developments focus on ATACSeq data analysis.

{% bibliography --query @misc[subject=singlecell] %}
{% bibliography --query @article[subject=singlecell] %}

### Point process modeling in genomics

Recent projects focus on the spatial modeling of genomic data using point processes. With [E. Roquain]() and [P. Reynaud-Bouret]() we developed a testing procedure based on continuous testing to compare maps of genomic features, while controling for multiple (continuous) error rates. With [A. Bonnet]() and  [V. Rivoirard]() we develop Hawkes models to catch spatial interactions between genomic features.

{% bibliography --query @misc[subject=pointprocess] %}
{% bibliography --query @article[subject=pointprocess] %}


### Replication origins in vertebrates

Together with [M.-N. Prioleau]() and [L. Duret](https://lbbe.univ-lyon1.fr/-Duret-Laurent-.html) we work on the spatial program of replication at fine scales in vertebrate genomes. We characterized replication origins in humans by analyzing Oriseq data, and we determined epigenetic signatures that characterize the spatio temporal program of replication. Our method of peak detection using scan statistics can be reproduced using <a href="{{ '/assets/soft/scan-method.zip' | prepend: site.baseurl | prepend: site.url }}">this code</a> (with a toy example). With [F. Massip]() We are currently working on the conservations of replication origins in vertebrates, and on the better characterization of these epigenomic signatures, especially with ATACSeq data.

{% bibliography --query @article[subject=replication] %}

### Functional Data analysis

With [S. Lambert-Lacroix](http://membres-timc.imag.fr/Sophie.Lambert/), [G. Marot](http://cerim.univ-lille2.fr/pages-individuelles-chercheurs/pages-perso-guillemette-marot/guillemette-marot-briend.html), and [J. M. Giacofci](https://perso.univ-rennes2.fr/joyce.giacofci) we developed curve clustering models that account for an inter-individual variability throught mixed functional models. We also developed a shrinkage method for functional mixed models. More recent developments concern functional models in the Poisson case, in collaboration with [V. Rivoirard](https://www.ceremade.dauphine.fr/~rivoirar/) and [A. Roche](https://www.ceremade.dauphine.fr/~aroche/).

{% bibliography --query @article[subject=functional] %}

### Population Genomics and sex-linked genes

With [G. Marais](https://lbbe.univ-lyon1.fr/-Marais-Gabriel-.html), [N. Lartillot](https://lbbe.univ-lyon1.fr/-Lartillot-Nicolas-.html), [Jos Kafer](https://lbbe.univ-lyon1.fr/-Kafer-Jos-.html) and [A. Muyle]() we developed a statistical approach to infer sex-linked genes based on a controlled cross. This method is available with the sexdetector software and we are currently developing a population-based model to enrich this method.

{% bibliography --query @misc[subject=genomics] %}
{% bibliography --query @article[subject=genomics] %}

# Past Projects

### CGH microarrays analysis and segmentation models

In collaboration with [S. Robin](https://www6.inra.fr/mia-paris/Equipes/Membres/Stephane-Robin) and [E. Lebarbier](https://www6.inra.fr/mia-paris/Equipes/Membres/Emilie-Lebarbier) developed segmentation models for the analysis of array CGH data, an array technology that maps chromosomal aberrations. Methodological questions associated with segmentation are : finding an efficient algorithm to find the breaks by dynamic programming, and estimating the number of breaks by model selection. The purpose can also be to analyse multiple sample datasets. 

{% bibliography --query @article[subject=segmentation] %}

### Biological networks, random graphs and motifs

To study the topology of complex networks we (with [S. Robin](https://www6.inra.fr/mia-paris/Equipes/Membres/Stephane-Robin) and [J.-J. Daudin](https://www6.inra.fr/mia-paris/Equipes/Membres/Jean-Jacques-Daudin)) proposed the Mixnet model, also known as the Stochastic Block Model, to cluster nodes of a network that share the same connectivity via a generalization of mixture models to network data. As a result, MixNet provides a synthetic picture of the main connectivity patterns that make the network. A challenge when using these models lies in the variational algorithm to estimate the parameters. We proposed an online version of such algorithm to deal with very large networks (with [C. Ambroise]() and [V. Miele]()).

Another way to study the architecture of networks is to study their basic subunits, building blocks or network motifs. The statistical question associated with network motifs is the question of their exceptionality. Are there motifs that occur more than expected in biological network ? This question is related to the distribution of the count of some subgraphs in random graphs. 

{% bibliography --query @article[subject=networks] %}
