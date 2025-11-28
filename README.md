# Fear & Greed Sentiment Analysis on Trading Behaviour

## Author
*Supritha*

## Project Overview
This project analyzes how trading performance changes under different market sentiments — specifically *Fear vs Greed*. The project merges historical trading data with the Bitcoin Fear & Greed Index to study behavior, risk-taking, and profitability.

## Datasets Used
1. Historical Trader Data
2. Fear & Greed Index

## Methodology
- Data cleaning and preprocessing
- Time conversion and merging
- KPI computation:
  - Number of trades
  - Total volume
  - Average & median PnL
  - Win rate
  - Average leverage
- Visualization of KPIs and Daily PnL
- Statistical test (Fear vs Greed performance comparison)

## Files in this Project
| File | Description |
|------|-------------|
| ds_Supritha_Fear_Greed_Analysis.ipynb | Main notebook |
| merged_with_sentiment.csv | Merged dataset |
| kpis_by_sentiment.csv | KPIs for Fear vs Greed |
| report.pdf | Final report |
| outputs/ | All graphs |
| raw_data/ | Original datasets |

## How to Run
1. Open the notebook in Google Colab
2. Upload both CSV datasets into Colab
3. Run all cells in order
4. Outputs will be saved automatically

## Conclusion
Trading behavior changes significantly depending on market emotion. The KPI analysis highlights differences in profitability and risk-taking during Fear vs Greed periods.