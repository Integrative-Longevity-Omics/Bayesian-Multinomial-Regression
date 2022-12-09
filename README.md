# Bayesian Differential Analysis of Cell Type Proportions: Short Report

Code for Manuscript in Progress: Karagiannis, TT, Monti, S, and Sebastiani, P. Bayesian Differential Analysis of Cell Type Proportions: Short Report.

## Dependencies
* Before running the Bayesian multinomial model, make sure that R and JAGS are installed.
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

scCODA python application to scRNA-seq data of PBMCs across age for comparison: scCODA_Comparison.ipynb
 
