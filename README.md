# Trader Behavior Analysis Based on Bitcoin Market Sentiment

## Overview

This project analyzes the relationship between Bitcoin market sentiment and trader performance using historical trading data from Hyperliquid and the Bitcoin Fear & Greed Index.

The objective is to identify patterns between market sentiment (Fear, Greed, Neutral, Extreme Greed) and trading outcomes, helping traders make more informed decisions.

---

## Datasets Used

### 1. Hyperliquid Historical Trader Data
Contains:
- Account
- Coin
- Execution Price
- Size Tokens
- Size USD
- Side
- Timestamp
- Closed PnL
- Fee
- Trade ID

### 2. Bitcoin Fear & Greed Index
Contains:
- Date
- Classification
- Value

---

## Data Processing

### Steps Performed

1. Loaded both datasets using Python (Pandas).
2. Converted Unix timestamps into datetime format.
3. Created a common date column.
4. Merged trader data with sentiment data.
5. Cleaned and validated the merged dataset.
6. Performed exploratory data analysis (EDA).
7. Created Power BI dashboard for visualization.

---

## Tools Used

- Python
- Pandas
- Jupyter Notebook
- Power BI

---

## Key Findings

### Profit by Sentiment

| Sentiment | Total Profit |
|------------|------------|
| Fear | 4.88M |
| Greed | 1.69M |
| Neutral | 0.18M |
| Extreme Greed | 0.17M |

### Average Profit per Trade

| Sentiment | Avg PnL |
|------------|------------|
| Greed | 152.05 |
| Fear | 88.49 |
| Neutral | 55.48 |
| Extreme Greed | 25.42 |

### Win Rate

| Sentiment | Win Rate |
|------------|------------|
| Extreme Greed | 49.0% |
| Fear | 45.9% |
| Greed | 42.7% |
| Neutral | 31.2% |

### Top Profitable Coins

1. @107
2. HYPE
3. SOL
4. ETH
5. BTC

---

## Dashboard

The Power BI dashboard includes:

- Total Trades
- Total Profit
- Average Profit per Trade
- Win Rate
- Profit by Sentiment
- Average Profit by Sentiment
- Win Rate by Sentiment
- Top 10 Coins
- Top 10 Traders
- Trade Distribution by Sentiment

---

## Conclusion

The analysis shows a significant relationship between market sentiment and trading performance.

- Fear periods generated the highest overall profits due to high trading activity.
- Greed periods produced the highest average profit per trade.
- Extreme Greed achieved the highest win rate.
- Neutral sentiment showed the weakest performance.

These findings suggest that market sentiment can be a valuable input for designing sentiment-aware trading strategies.

---

## Author

**Navaneetha K**

B.Tech Artificial Intelligence & Data Science
