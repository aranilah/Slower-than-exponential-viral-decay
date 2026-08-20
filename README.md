
# Code repository for "Slower-than-exponential viral decay is prevalent and can reshape virus-microbe dynamics"

Akash Arani, Paul Fremont, Emma Wachter, Joshua S. Weitz

## General Description

This repository contains all the code need to replicate the figures and analysis show in the paper "Slower-than-exponential viral decay is prevalent and can reshape virus-microbe dynamics". The code is written in Python 3. 


## Running the code

You will need python packages numpy, matplotlib, scipy, math, pandas,  statsmodels, lmfit, and statistics. You will also need an IDE that runs .ipynb files.

## File descriptions: 

### Biphasic_vs_exp.ipynb: 
#### Biphasic vs exponential analysis for the 17 datasets. Produces Fig 1, 2, and S1

### Aggregation_to_biphasic_mapping.ipynb:
#### Mapping of biphasic model to aggregation model and compares biphasic vs aggregation across the 6 chosen datasets. Produces Fig 4 and S2

### Virus_Host_SteadyState_dynamics.ipynb: 
#### Implements aggregation into full virus-host model and calculates the steady state dynamics. Produces Figure 5

### Decay_datasets.xlsx
#### Contains the raw viral decay data collected via PlotDigitizer for all 17 datasets
