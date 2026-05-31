# Emergent frequency-dependent selection predicts mutation outcomes in complex ecological communities

## Overview

This repository contains the code used in our paper "Emergent frequency-dependent selection predicts mutation outcomes in complex ecological communities", published on bioRxiv and arXiv. 

## Authors

- **Shing Yan Li**
- **Zhijie Feng**
- **Akshit Goyal**
- **Pankaj Mehta**

## Jupyter Notebooks

This repository includes three Jupyter notebooks for producing simulation results in our paper, one notebook for analyzing the human gut microbiome data, and one notebook for generating the figures.

1. **`pop_gen_glv.ipynb`**
   - Simulations for generalized Lotka-Volterra model, generating the results in the **main text**.

2. **`pop_gen_self_renew_crm.ipynb`**
   - Simulations for MacArthur consumer-resource model, i.e., with self-renewing resources.

3. **`pop_gen_external_supply_crm.ipynb`**
   - Simulations for consumer-resource model with externally supplied resources.

4. **`data/time_series.ipynb`**
   - Analysis of the human gut microbiome data in Roodgar et al. and generation of Figure 5 in our paper.

5. **`figures/plots.ipynb`**
   - Generation of figures in our paper using data from the above three notebooks.

## Data

The `pickle` files for simulation results used in the figures are in the `figures` folder. The human gut microbiome data used in Figure 5 are in the `data` folder.