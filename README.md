# Bayesian differential cell type proportion analysis: Bayesian multinomial logistic model to analyze the distributions of cell types

Code for Manuscript in Progress: Karagiannis, TT, Monti, S, and Sebastiani, P. Bayesian differential cell type proportion analysis.

## Dependencies
* Before running the Bayesian multinomial logistic model, make sure that R and JAGS are installed.
* Install the following R packages if not installed already:

```
install.packages(tidyverse)
install.packages("rjags")
install.packages("coda")
install.packages("hablar")
install.packages("patchwork")
```

## Scripts

Model configuration and initializations in rjags: rjags_multinom.R

Model application including parameter inference and obtaining posterior distributions:

- simulated toy dataset: Vignette_ToyData.Rmd

- scRNA-seq data of PBMCs across age: Vignette_scRNA_PBMC.Rmd
 
