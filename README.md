# Introduction
### Estimating the volume of the exit tunnel of _Escherichia coli_ ribosomes

The ribosome exit tunnel is a non-uniformly shaped conduit that interacts with the nascent proteins that it translates. This unique shape is contributed to by ribosomal rRNA and protruding loops of ribosomal proteins that line the tunnel wall. 

In (DOI: 10.7554/eLife.36326), we examined how the shape of the ribosome exit tunnel can influence where proteins can fold. The study utilises ribosomes with varying tunnel volumes, which was achieved by removing the protruding loops of the ribosomal proteins that contribute towards the unique shape of the tunnel. 

A part of the study involved estimating the volume of the _Escherichia coli_ ribosome and its mutant variants. We estimated the volumes using [POVME 2.0](https://git.durrantlab.pitt.edu/jdurrant/POVME) and we describe the process here. 

### The Challenge
The tunnel is **not** uniform in its shape - ribosomes are comprised of mostly rRNA and therefore not compact. Moreover, the "main" channel is connected to several "minor channels". 
An analogy that we find useful is that of a river (the channel) that flows into the sea (the cytoplasm) and is joined by several tributaries (minor channels) at the delta (the exit). The challenge is to estimate the exact location of river and thereafter the volume of water that the river carries without disturbing its tributaries. 

### Why POVME 2.0? 

POVME 2.0 is a software that has been used to calculate the volume of binding pockets in proteins. We chose it for this study because its simple algorithm would enable us to help define a channel i.e. identify the location of the "river". We were also guided by the knowledge that a nascent peptide traverses the ribosome tunnel through to the cytoplasm and POVME 2.0 allowed us to identify and define the boundaries.   
POVME 2.0 is easy to use and enabled us to make few assumptions about our experimental model, we could change the radii of the spheres used, add or remove single components, and obtain results rapidly. This allowed numerous attempts at estimating the approximate volume of the _E.coli_ ribosome exit tunnel and the variants of it used in our study.   

### Why this repository? 

Although our work has been published, we would like to share our files and raw data in the interest of transparency and reproducibility in research. We hope it is useful to anyone who is interested in estimating volumes of the ribosome exit tunnel. 

### About us
We think open science is cool and hope you do too! 
