# Dataset: ESOL (Delaney)
## Overview

[ESOL](https://deepchemdata.s3-us-west-1.amazonaws.com/datasets/delaney-processed.csv) is a regression dataset from MoleculeNet containing water solubility data (log solubility in mols per liter) for a collection of 1,128 common organic small molecules. The target property is the log-scaled solubility, making it a useful benchmark for evaluating models in molecular property prediction.

### Source: 
Delaney, J. S. (2004). "ESOL: Estimating Aqueous Solubility Directly from Molecular Structure." J. Chem. Inf. Comput. Sci.

### Type: 
Regression

### Target: 
Log solubility (logS) in mol/L

### Size: 
1,128 molecules

### Features: 
SMILES strings representing molecular structures

## Task

The task is to predict the log water solubility of each molecule given its structure. This is a real-valued regression problem.
