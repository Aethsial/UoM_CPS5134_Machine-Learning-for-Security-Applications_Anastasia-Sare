# UoM_CPS5134_Machine-Learning-for-Security-Applications_Anastasia-Sare

Anastasia Sare

This repository contains my CPS5134 coursework for Machine Learning for Security Applications. The work focuses on network intrusion detection using supervised machine learning on flow-based intrusion datasets (CIC-IDS2017-derived data).

---

## Project overview
The main deliverable is a Jupyter notebook that:
- Loads and preprocesses the dataset,
- Trains and evaluates ML models for intrusion detection,
- Reports results (including class-aware metrics).

---

## Repository structure
- `CPS5134_Machine Learning for Security Applications_JupyterNotebook_Anastasia Sare.ipynb`  
  Main notebook (data prep > training > evaluation).

- `CPS5134_Machine Learning for Security Applications_JupyterNotebook_Results_Anastasia Sare.pdf`  
  Exported results/figures from the notebook run.

---

## Setup
### Prerequisites
- Python 3.10+  
- Jupyter Notebook

### Main Python packages used
- numpy
- pandas
- scikit-learn
- xgboost
- matplotlib

---

## Datasets
### Source data
This project is based on CIC-IDS2017 (Canadian Institute for Cybersecurity, University of New Brunswick):  
- Official dataset page: https://www.unb.ca/cic/datasets/ids-2017.html

A Kaggle versio was used for this coursework:  
- https://www.kaggle.com/datasets/chethuhn/network-intrusion-dataset

### Generated / processed datasets (GitHub Release)
Some processed/generated dataset files were too large to store directly in the repository, so they are provided via a GitHub Release:

- Release name: Generated Datasets
- Tag: Datasets
- Release page: https://github.com/Aethsial/UoM_CPS5134_Machine-Learning-for-Security-Applications_Anastasia-Sare/releases/tag/Datasets
