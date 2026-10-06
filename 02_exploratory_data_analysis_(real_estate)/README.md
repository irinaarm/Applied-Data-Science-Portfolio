# Real Estate Market Analysis

## Business problem

Determine the factors that influence residential property values in Saint Petersburg and the surrounding region, and identify parameters useful for detecting anomalous listings.

## Approach

- Cleaned missing values, anomalies, and inconsistent data types.
- Engineered price, date, floor, and distance-related features.
- Analyzed property characteristics, geographic patterns, and publication timing.
- Compared the city center with the wider market.

## Result and recommendation

Total area and number of rooms were the strongest price drivers. Properties in central Saint Petersburg were generally larger, had more rooms and higher ceilings, and commanded higher prices. A radius of approximately seven kilometres was identified as a practical boundary for the city-center segment. These variables can be used as inputs for automated listing validation.

## Tools

Python, pandas, Matplotlib

## Notebook

[Open the analysis](exploratoy_data_analysis_eng.ipynb)

## Data availability

The original educational dataset is not included. The notebook expects `real_estate_data.csv` in a local `data/` directory.
