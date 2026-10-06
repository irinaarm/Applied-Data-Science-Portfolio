# Gold Recovery Prediction

## Business problem

Predict gold-recovery efficiency from ore-processing parameters to help avoid operating configurations with unprofitable characteristics.

## Approach

- Validated the recovery calculation and inspected unavailable test features.
- Analyzed metal concentrations and particle-size distributions across processing stages.
- Compared Linear Regression, Decision Tree, and Random Forest models using cross-validation.
- Evaluated performance with the project-specific final sMAPE metric.

## Final metrics

- **Linear Regression final sMAPE:** 7.59%
- **Dummy baseline final sMAPE:** 8.56%

## Business recommendation

Use the linear model as a transparent baseline, but validate it on more recent production data and investigate the removed missing-value cases before operational deployment.

## Tools

Python, pandas, NumPy, scikit-learn, Matplotlib, Seaborn

## Notebook

[Open the analysis](gold_recovery_eng.ipynb)

## Data availability

The original educational datasets are not included. The notebook expects the three `gold_recovery_*_new.csv` files in a local `data/` directory.
