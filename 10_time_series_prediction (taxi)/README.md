# Time-Series Demand Forecasting

## Business problem

Forecast airport taxi demand one hour ahead so the company can attract enough drivers during peak periods.

## Approach

- Resampled order data to hourly frequency.
- Analyzed trend and daily and weekly seasonality.
- Created calendar, lag, and rolling-window features.
- Compared Linear Regression, Random Forest, LightGBM, and CatBoost on a chronological split.

## Final metric

Linear Regression achieved a test **RMSE of 34.63**, exceeding the project requirement of RMSE below 48. A previous-value baseline produced RMSE of 58.82.

## Business recommendation

Use the forecast to support hourly driver allocation, while monitoring missed demand spikes and retraining as demand patterns change.

## Tools

Python, pandas, scikit-learn, statsmodels, LightGBM, CatBoost, Matplotlib, Seaborn

## Notebook

[Open the analysis](taxi_eng.ipynb)

## Data availability

The original educational dataset is not included. The notebook expects `taxi.csv` in a local `data/` directory.
