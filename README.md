# Marketing Mix Modeling (MMM) - DT MART

A Marketing Mix Model built in Python to quantify the revenue contribution of each marketing channel, identify diminishing returns, and recommend an optimized budget allocation for DT MART, a retail brand.

## Dataset

Source: [DT MART Market Mix Modeling - Kaggle](https://www.kaggle.com/datasets/datatattle/dt-mart-market-mix-modeling)

The dataset contains 12 months of marketing and sales data (July 2015 to June 2016) across seven CSV files including transaction-level sales, monthly aggregated revenue, marketing channel spend, and Net Promoter Scores.

## Project Steps

1. Environment Setup and Data Ingestion
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing and Feature Engineering
4. Marketing Mix Model Building (OLS Regression)
5. Channel Contribution Analysis
6. Diminishing Returns and Saturation Curves
7. Budget Optimization Recommendations

## Key Findings

- Model achieved R-squared of 0.977 using 6 features on 12 monthly observations
- Affiliates is the most cost-efficient channel, delivering 19.1% revenue contribution from only 9.23% of total budget
- Sponsorship consumes 54.96% of budget but contributes only 17.7% of modeled revenue
- NPS score is the single strongest predictor of revenue at 43.4% contribution
- Budget reallocation from Sponsorship to Affiliates represents the highest impact optimization

## Tools and Libraries

- Python 3
- Pandas, NumPy
- Statsmodels (OLS Regression)
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

## Setup

1. Clone the repository

```
git clone https://github.com/your-username/marketing-mix-modeling-dt-mart.git
```

2. Install dependencies

```
pip install pandas numpy statsmodels scikit-learn matplotlib seaborn kaggle
```

3. Add your Kaggle API key (`kaggle.json`) to the root directory or upload it when prompted in Colab

4. Open the notebook and run all cells in order

```
Marketing_Mix_Modeling__MMM__DT_MART.ipynb
```

## Author

Muhammad Fiaz
