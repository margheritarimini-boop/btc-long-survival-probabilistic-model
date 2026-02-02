# Probabilistic Long-Survival Model in Advanced Biliary Tract Cancer

This repository hosts an online calculator implementing a probabilistic
clinical–molecular model for estimating the probability of long survival
(overall survival >18 months) in patients with advanced biliary tract cancer.

## Model description
The model is based on a multivariable logistic regression including:
- ECOG performance status (0 vs >0)
- Neutrophil-to-lymphocyte ratio (<3 vs ≥3)
- Prior surgical resection (yes/no)
- Disease stage (locally advanced vs metastatic)
- PALB2 mutation status
- PBRM1 mutation status

Regression coefficients and methodological details are reported in the
associated manuscript.

## How to use
Open the Excel file and enter binary values (0/1) for each variable.
The calculator will return the estimated probability of long survival.

## Intended use
This tool is intended for research and decision-support purposes only.
It does not replace clinical judgment.
