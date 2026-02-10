# Anything.ai – Data Science Assignment (Round-0)

## Objective
The objective of this assignment is to analyze the relationship between
trader behavior and overall Bitcoin market sentiment using the
Fear & Greed Index.

## Datasets Used
1. Fear & Greed Index  
   - Provides daily market sentiment classified as Fear or Greed.

2. Historical Trader Data (Hyperliquid)  
   - Contains transaction-level trading data including trade size,
     execution price, position details, and closed PnL.

## Methodology
- Cleaned and standardized timestamp formats.
- Merged trader data with market sentiment at daily granularity.
- Engineered features such as trade volume and profitability.
- Performed exploratory data analysis to compare trader behavior
  during Fear and Greed market conditions.

## Key Insights
- Traders exhibit higher trade volumes during Greed periods,
  indicating increased risk appetite.
- Profitability is comparatively more stable during Fear periods.
- Greed markets show higher volatility, suggesting aggressive trading behavior.

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## Files Included
- `notebook_1.ipynb` – Google Colab notebook containing full analysis.
- `csv_files/` – Raw datasets used in the analysis.
- `outputs/` – Generated plots and visualizations.
- `ds_report.pdf` – Summary of insights and conclusions.

## Google Colab Notebook
The complete analysis was performed in Google Colab.

Notebook link:
https://colab.research.google.com/drive/1Wqh5Iioh0MwfEffCHOcbMJltaRWaqVrU?usp=sharing

## Notes
All analysis was performed in Google Colab.
The repository structure strictly follows the assignment instructions.
