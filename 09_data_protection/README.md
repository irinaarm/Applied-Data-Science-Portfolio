# Personal Data Protection

## Business problem

Transform insurance-customer data so personal attributes are obscured without reducing the quality of a Linear Regression model.

## Approach

- Derived the effect of multiplying features by an invertible matrix.
- Generated a transformation matrix and encoded the feature set.
- Trained equivalent Linear Regression models on original and transformed data.
- Compared their R² scores on aligned validation samples.

## Final metrics

- **Original-data R²:** 0.423077
- **Transformed-data R²:** 0.423077

## Business recommendation

The matrix transformation preserves Linear Regression quality and can be used as an educational demonstration of reversible feature obfuscation. Production use would require secure key management and a formal privacy and threat assessment.

## Tools

Python, pandas, NumPy, scikit-learn, Matplotlib, Seaborn, Plotly

## Notebook

[Open the analysis](project_data_security_eng.ipynb)

## Data availability

The original educational dataset is not included. The notebook expects `insurance.csv` in a local `data/` directory.
