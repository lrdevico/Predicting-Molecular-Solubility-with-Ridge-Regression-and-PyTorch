# Predicting Molecular Solubility with Ridge Regression and PyTorch

##  About this Project

This repository contains my **first machine learning project**, developed to help me gain a better understanding of how machine learning models work and how they are structured. It serves as an introduction to building, training, and evaluating regression models using both **scikit-learn** and **PyTorch**.

The goal is to predict the **aqueous solubility (`logS`)** of chemical compounds based on four molecular descriptors.

---

## Dataset

- **Name**: Delaney solubility dataset with descriptors  
- **Original Source**: [Data Professor GitHub Repository](https://github.com/dataprofessor/data)  
- **Direct CSV**:  
  [https://raw.githubusercontent.com/dataprofessor/data/refs/heads/master/delaney_solubility_with_descriptors.csv](https://raw.githubusercontent.com/dataprofessor/data/refs/heads/master/delaney_solubility_with_descriptors.csv)  
- **Features used**:
  - `MolLogP`
  - `MolWt`
  - `NumRotatableBonds`
  - `AromaticProportion`
- **Target**: `logS` (aqueous solubility)

> ℹ️ Credit to [@dataprofessor](https://github.com/dataprofessor) for making the dataset available.

