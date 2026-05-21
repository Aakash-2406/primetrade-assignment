# Trader Performance vs Market Sentiment Analysis

## Objective
Analyze the relationship between Bitcoin market sentiment (Fear/Greed) and trader behavior/performance using Hyperliquid trading data.

## Datasets
1. Bitcoin Fear & Greed Index
2. Hyperliquid Historical Trader Data

## Methodology
- Cleaned and processed datasets
- Converted timestamps into datetime format
- Merged datasets using daily dates
- Analyzed:
  - PnL distribution
  - Trade sizes
  - Trading frequency
  - Trader segmentation
  - Market sentiment behavior

## Key Insights
- Greed periods showed higher profit opportunities but larger volatility.
- Trade sizes increased during optimistic sentiment conditions.
- Frequent traders appeared more profitable during strong momentum periods.
- Large position sizes increased both profitability and risk exposure.

## Strategy Recommendations
1. Reduce aggressive exposure during Fear periods.
2. Increase participation selectively during strong Greed trends.
3. Maintain disciplined position sizing for long-term consistency.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook