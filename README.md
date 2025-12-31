## Files
- notebook_1.ipynb - main analysis notebook
- csv_files - input datasets
- outputs - generated plots

# Trader Behavior vs Market Sentiment Analysis

## Objective
Analyze how trader profitability, risk, and trading behavior vary across
different market sentiment regimes (Fear vs Greed).

## Datasets
- Historical Trader Data (Hyperliquid) – linked due to size constraints
- Bitcoin Fear & Greed Index

## Approach
- Cleaned and normalized timestamps
- Aligned daily sentiment with trade-level data
- Analyzed PnL under Fear vs Greed regimes

## Key Insights
- Fear periods show higher trading activity and higher total PnL
- Greed periods show higher average PnL per trade

## Tools
- Python (Pandas, Matplotlib)
- Google Colab
- GitHub

## Data Access

Due to GitHub file size limitations, the full historical trader dataset
(>25MB) is not uploaded to this repository.

The dataset can be accessed from the original source:
- Historical Trader Data: https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjV
s/view?usp=sharing

- Fear & Greed Index: https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-
mnrYv_nhSf/view?usp=sharing

## Conclusion

The analysis shows that market sentiment has a clear impact on trading performance.
Trades executed during fear periods were more frequent and resulted in higher total profit,
while greed periods had fewer trades but higher average profit per trade.
This suggests that trader behavior changes with market psychology.
