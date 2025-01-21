# Beta-Binomial-Dose-Response-Models-for-Salmonella-data

## Overview
This repository demonstrates the use of a hierarchical beta-binomial dose-response model to analyze Salmonella epidemiological data. The model investigates strain-specific variability and predicts infection probabilities for new strains.\\

The project employs Bayesian inference with OpenBUGS and R for parameter estimation, showcasing advanced data analysis and visualization techniques. It is designed for scientific reproducibility and can be used as a portfolio piece.

 ## Features

-**Hierarchical Model:** Incorporates hyperparameters for strain-specific dose-response variability.
-**Bayesian Inference:** Implements MCMC to estimate parameters using OpenBUGS.
-**Predictive Analysis:** Includes predictions for a new strain.
-**Visualization:** Generates detailed plots for MCMC convergence, contour analysis, histograms, and dose-response curves.

 ## Prerequisites

 To reproduce the analysis, ensure the following are installed:

 ### R Packages
 install.packages(c("R2OpenBUGS", "ggplot2", "MASS", "tidyr", "grid", "gridExtra", "coda", "Hmisc"))

### OpenBUGS
Download and install OpenBUGS from https://openbugs.software.informer.com/
