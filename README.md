# Project IV – Code Repository

This repository contains all the R code used for my Bayesian Computation for Stochastical Dynamical Systems report, focusing on implementing the Pseudo Marginal Metropolis-Hastings (PMMH) algorithm and a Gibbs sampler for two models: Lotka-Volterra (LV) and Geometric Brownian Motion (GBM).

## How to Use This Repository

### 1. Start with the Core Scripts
Begin by looking at the main scripts:
- **Pseudo-marginal Metropolis-Hastings for Lotka-Volterra**
- **Pseudo-marginal Metropolis-Hastings for Geometric Brownian Motion**
- **Gibbs Sampler**

These are the central parts of the project and contain the core algorithms used in the analysis.

### 2. Generate the Figures and Tables
Once you’ve run the core scripts, you can move on to the plotting scripts:
- **PMMH for LV observation time**
- **PMMH for LV partition intervals**
- **PMMH for GBM figures**

### 3. Additional Plots and Analysis
There are a couple of extra sections worth checking out:
- The **"Extra Plots"** file contains additional visualisations referenced in Sections 2 and 3 of the report.
- The **Lotka-Volterra Analytical vs Numerical** section looks at how the analytical and numerical solutions for the LV model compare.

## A Note on Computation Time
Some of these methods — especially PMMH — are computationally heavy, so don’t be surprised if certain scripts take a while to run.

## Summary
To get the most out of this repo:
1. Start with the core PMMH and Gibbs scripts.
2. Use the plotting scripts to recreate the figures and tables from the report.
3. Explore the additional files if you’re interested in the less relevant figures

Thanks for checking it out!
