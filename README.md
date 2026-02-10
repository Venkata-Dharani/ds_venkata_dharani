# Trader Performance vs Market Sentiment
### Data Science / Analytics Intern – Round-0 Assignment

## Objective
Analyze how Bitcoin market sentiment (Fear vs Greed) influences
trader behavior and performance on the Hyperliquid trading platform,
with the goal of identifying actionable trading insights.

## Datasets Used
1. Bitcoin Market Sentiment (Fear & Greed Index)
   - Daily sentiment classification: Fear / Greed
2. Historical Trader Data (Hyperliquid)
   - Transaction-level trading data including trade size,
     execution price, timestamps, and closed PnL

## Methodology
- Inspected datasets for structure, missing values, and duplicates
- Converted timestamps and aligned both datasets at daily granularity
- Engineered key metrics such as trade volume, win rate, and trade frequency
- Performed sentiment-based comparative analysis
- Derived actionable trading insights

## Key Insights
- Higher trade volume and risk-taking behavior observed during Greed periods
- Profitability is more stable during Fear periods
- Increased activity during Greed does not significantly improve win rate

## Strategy Recommendations
- Reduce leverage during Fear periods for better risk-adjusted returns
- Maintain strict position sizing discipline during Greed markets

## Files Included
- `notebook_1.ipynb` – Complete Google Colab analysis
- `outputs/` – Generated charts and visualizations
- `ds_report.pdf` – Summary of methodology, insights, and strategies

## Google Colab Notebook
https://colab.research.google.com/drive/1Wqh5Iioh0MwfEffCHOcbMJltaRWaqVrU?usp=sharing

## Dataset Access
Due to GitHub file size limitations, the original datasets are not
uploaded to this repository. They can be accessed using the official
links provided in the assignment instructions.

## Assignment Coverage
This submission addresses:
- Part A: Data preparation and daily alignment
- Part B: Performance and behavior analysis
- Part C: Actionable trading strategy recommendations

## Note on Dataset Files
The original datasets are relatively large in size and exceed
GitHub’s file upload limits. Hence, the raw CSV files are not
included in this repository.

All analysis was performed using the official datasets provided
in the assignment links, and the notebook is fully reproducible
when those datasets are downloaded locally.
