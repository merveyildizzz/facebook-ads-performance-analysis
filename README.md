# Facebook Ads Performance Analysis

## Project Objective

This project analyzes Facebook Ads campaign performance using Python, Pandas, Matplotlib, and Seaborn. The goal is to understand spending patterns, campaign profitability, and relationships between key advertising metrics.

## Dataset

The dataset includes Facebook advertising performance data with metrics such as:

- Ad date
- Campaign name
- Total spend
- Total impressions
- Total clicks
- Total value
- CPC
- CPM
- CTR
- ROMI

## Analysis Steps

- Loaded and reviewed the dataset
- Converted the date column into datetime format
- Filtered the data for 2021
- Analyzed daily ad spend and ROMI trends
- Used rolling averages to smooth short-term changes
- Compared campaign performance by total spend and ROMI
- Visualized ROMI distribution with boxplot and histogram
- Created a correlation heatmap
- Used linear regression visualization to explore the relationship between total spend and total value

## Key Insights

- Total spend and total value have a very strong positive relationship.
- Higher advertising spend generally increases revenue.
- Higher spend does not necessarily guarantee higher profitability.
- ROMI varies across campaigns, showing that campaign efficiency should be evaluated separately from revenue.
- Rolling averages help make daily performance trends easier to understand.

## Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project File

The full analysis is available in the Jupyter Notebook:

`facebook_ads_performance_analysis.ipynb`

## Conclusion

This project helped me practice data cleaning, aggregation, visualization, and business interpretation using advertising performance data. It shows how marketing data can be analyzed to support better campaign decisions.
