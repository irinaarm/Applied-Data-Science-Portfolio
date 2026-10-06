# Telecom Plan Revenue Analysis

## Business problem

Determine which prepaid plan generates more value for the operator and should receive greater marketing support.

## Approach

- Aggregated monthly calls, messages, and internet usage by customer.
- Calculated monthly revenue including overage charges.
- Compared customer behavior and revenue distributions by plan.
- Tested differences between plans and between Moscow and other regions.

## Result and recommendation

Average revenue differed significantly between the two plans, while no significant revenue difference was found between Moscow and other regions. The Ultra plan produced higher revenue per user and was recommended for additional promotion, subject to the company’s broader pricing and market strategy.

## Tools

Python, pandas, NumPy, SciPy, Matplotlib, Plotly

## Notebook

[Open the analysis](statistical_data_analysis_eng.ipynb)

## Data availability

The original educational datasets are not included. The notebook expects `calls.csv`, `internet.csv`, `messages.csv`, `tariffs.csv`, and `users.csv` in a local `data/` directory.
