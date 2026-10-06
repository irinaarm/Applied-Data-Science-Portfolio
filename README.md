# Applied Data Science and Machine Learning Portfolio

This repository contains ten end-to-end projects completed during the Yandex Practicum Data Science program. The portfolio covers data analysis, statistical modelling, supervised learning, business-focused machine learning and time-series forecasting. I now apply this foundation to supply chain planning, process automation and AI-enabled decision support.

## Featured projects

### [Time-Series Demand Forecasting](10_time_series_prediction%20%28taxi%29/taxi_eng.ipynb)

- **Business problem:** Forecast airport taxi demand one hour ahead so the company can attract enough drivers during peak periods.
- **Approach:** Resampled order data hourly, analyzed trend and daily/weekly seasonality, created lag and rolling-window features, and compared regression models on a chronological split.
- **Models used:** Linear Regression, Random Forest, LightGBM, and CatBoost.
- **Final metric:** Test RMSE **34.63**, exceeding the project requirement of RMSE below 48.
- **Business recommendation:** Use the Linear Regression forecast to support hourly driver allocation, while monitoring missed demand spikes and retraining as demand patterns change.

### [Machine Learning for Business Decisions](07_ML_in_business%20%28oil%26gas%29/project_oil_wells_eng.ipynb)

- **Business problem:** Select the oil-production region expected to deliver the highest profit while keeping the probability of loss within acceptable limits.
- **Approach:** Predicted reserves with linear regression, ranked candidate wells, calculated break-even economics, and estimated profit distributions and downside risk with 1,000 bootstrap samples.
- **Models used:** Linear Regression with bootstrap-based profit and risk simulation.
- **Final metric:** Region 2 achieved mean predicted profit of **0.515 billion** monetary units, a **95% confidence interval of 0.069–0.932 billion**, and **1.0% loss risk**.
- **Business recommendation:** Develop Region 2 because it combines the highest expected profit with the lowest estimated risk of loss.

### [Customer Churn Prediction](06_supervised_learning%20%28banking%29/project_bank_eng.ipynb)

- **Business problem:** Identify bank customers likely to leave so retention activity can focus on high-risk customers before churn occurs.
- **Approach:** Prepared customer data, encoded categorical variables, compared classification models, diagnosed class imbalance, and tested weighting, upsampling, and downsampling strategies.
- **Models used:** Logistic Regression, Decision Tree, and Random Forest.
- **Final metric:** Random Forest reached test **F1 = 0.603** and **ROC-AUC = 0.86** after upsampling the minority class by a factor of three.
- **Business recommendation:** Use churn scores to prioritize targeted retention campaigns, with intervention thresholds aligned to campaign cost and customer value.

## Full project portfolio

| # | Project | Business focus | Tools and methods |
|---:|---|---|---|
| 1 | [Borrower Default Risk Analysis](01_data_preprocessing_%28bank_loan%29/) | Identify factors associated with timely loan repayment | Python, pandas, data preprocessing |
| 2 | [Real Estate Market Analysis](02_exploratory_data_analysis_%28real_estate%29/) | Analyze property values and flag market anomalies | pandas, NumPy, visualization, EDA |
| 3 | [Telecom Plan Analysis](03_statistical_data_analysis_%28telecom%29/) | Compare customer behavior and mobile-plan economics | statistical analysis, hypothesis testing |
| 4 | [Video Game Sales Analysis](04_analysis_of_video_games_sales/) | Identify promising platforms, genres, and regional market patterns | pandas, SciPy, EDA |
| 5 | [Mobile Plan Recommendation](05_introduction_to_ML%28telecom%29/) | Recommend the most suitable mobile plan from usage behavior | classification, scikit-learn |
| 6 | [Customer Churn Prediction](06_supervised_learning%20%28banking%29/) | Prioritize customers for retention | classification, class balancing, Random Forest |
| 7 | [Machine Learning for Business Decisions](07_ML_in_business%20%28oil%26gas%29/) | Select an investment region under profit and risk constraints | regression, bootstrap simulation |
| 8 | [Gold Recovery Prediction](08_gold_recovery_prediction/) | Predict recovery efficiency in mineral processing | regression, custom metrics |
| 9 | [Personal Data Protection](09_data_protection/) | Protect customer data while preserving model quality | linear algebra, data transformation |
| 10 | [Time-Series Demand Forecasting](10_time_series_prediction%20%28taxi%29/) | Forecast hourly taxi demand | time series, feature engineering, regression |

## Technical stack

**Languages:** Python, SQL

**Core libraries:** pandas, NumPy, SciPy, scikit-learn, statsmodels, LightGBM, CatBoost, Matplotlib, Seaborn, Plotly

**Methods:** exploratory data analysis, statistical testing, classification, regression, ensemble learning, time-series forecasting, bootstrap risk analysis

## Certificate

[Yandex Practicum — Data Science Specialist](https://drive.google.com/file/d/17Wl2skRF5Ndfvwu1FWdAG8X6AjOf1Dxt/view?usp=sharing)
