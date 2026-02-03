# BTC Long-Survival Probabilistic Model

This repository provides an **online probabilistic calculator** to estimate the **individual probability of long survival** (overall survival >18 months) in patients with advanced biliary tract cancer (BTC), based on an integrated **clinical–molecular logistic regression model**.

The model is intended as a **clinical decision-support tool** to support risk stratification in clinically challenging scenarios.

---

## Model overview

The probabilistic model was developed from multivariable logistic regression analyses and includes **five baseline variables** independently associated with long survival.

### Clinical variables
- **ECOG performance status** (0 vs ≥1)  
- **Neutrophil-to-lymphocyte ratio (NLR)** (<3 vs ≥3)  
- **Carcinoembryonic antigen (CEA)** (≤3.8 vs >3.8)

### Molecular variables
- **PALB2 mutational status** (mutated vs wild-type)  
- **PBRM1 mutational status** (mutated vs wild-type)

The model outputs an **individual predicted probability (%) of long survival (OS >18 months)**.

---

## How to use the calculator

1. Download the Excel file:  
   **`LongSurvival_ProbabilisticCalculator_5var_PERCENT.xlsx`**

2. Enter **0 or 1** for each variable according to the definitions reported in the calculator:
   - `0` = reference / favorable category  
   - `1` = unfavorable category (or mutation present, where applicable)

3. The calculator automatically returns:
   - **Predicted probability of long survival (%)**

No additional calculations are required.

---

## Interpretation

- The output represents the **estimated probability** that a patient will achieve **overall survival longer than 18 months**.
- Higher values indicate a **higher likelihood of long survival**.
- In the associated study, patients in the **top 20% of predicted probability** represented a clinically enriched subgroup with substantially longer overall survival.

The model is **prognostic** and should be interpreted alongside clinical judgment.

---

## Disclaimer

This calculator is provided **for research and educational purposes only**.  
It is **not intended to replace clinical decision-making** and has not been prospectively validated for routine clinical use.

---

## Reference

If you use this calculator or repository, please cite the associated manuscript:

*Authors.* Development and validation of an integrated clinical–molecular probabilistic model to predict long survival in advanced biliary tract cancer. *Journal*, Year.
