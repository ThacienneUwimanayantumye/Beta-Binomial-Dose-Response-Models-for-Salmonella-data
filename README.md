# Hierarchical Beta-Binomial-Dose-Response-Model for Salmonella epidemiological data

## Overview
This repository demonstrates the use of a hierarchical beta-binomial dose-response model to analyze Salmonella epidemiological data. The model investigates strain-specific variability and predicts infection probabilities for new strains.

The project employs Bayesian inference with OpenBUGS and R for parameter estimation, showcasing advanced data analysis and visualization techniques. It is designed for scientific reproducibility and can be used as a portfolio piece.

 ## Features

- **Hierarchical Model:** Incorporates hyperparameters for strain-specific dose-response variability.
* **Bayesian Inference:** Implements MCMC to estimate parameters using OpenBUGS.
+ **Predictive Analysis:** Includes predictions for a new strain.
- **Visualization:** Generates detailed plots for MCMC convergence, contour analysis, histograms, and dose-response curves.

 ## Prerequisites

 To reproduce the analysis, ensure the following are installed:

 ### R Packages
 `install.packages(c("R2OpenBUGS", "ggplot2", "MASS", "tidyr", "grid", "gridExtra", "coda", "Hmisc"))`

### OpenBUGS
Download and install OpenBUGS from https://openbugs.software.informer.com/
## How to Reproduce the Analysis
### Step 1: Clone the Repository
`git clone [https://github.com/thacienneUwimanayantumye/Hierarchical-Beta-Binomial-Model.git](https://github.com/ThacienneUwimanayantumye/Beta-Binomial-Dose-Response-Models-for-Salmonella-data/tree/main)
cd Hierarchical-Beta-Binomial-Model`

### Step 2: Set Up the Environment
Ensure all required R packages are installed and OpenBUGS is properly configured.

### Step 3: Run the Analysis
1. Open hierarchical_model.Rmd in RStudio.
2. Knit the file to generate a complete report:
   - Set the output to PDF, HTML, or Word as needed.

### Results

**MCMC Diagnostics**
  The trace plots indicate convergence across all monitored parameters.
  
**Parameter Exploration**
The contour plots to depict the posterior density of log10 of the estimated parameters

**Dose-Response Curves**
The dose-response relationship is visualized with credible intervals and observed data points

## Dataset Description
The analysis uses a subset of Salmonella epidemiological data with the following columns:

- **log10dose**: Log-transformed dose levels.
- **Y**: Number of cases.
- **N**: Total number of individuals in the sample.
- **t**: Strain type (categorical variable).

## Future Work
- Enhance strain-specific parameter tuning.
- Compare hierarchical beta-binomial with other models (e.g., logistic regression).
- Expand analysis to additional datasets.
 .
