# Market Sentiment & Trader Behavior Analysis
Market Sentiment & Trader Behavior Analysis using Bitcoin Fear & Greed Index and trader data.


Analysis of how market sentiment (Fear vs Greed) impacts trader behavior and performance in crypto markets.

---

## Overview

This project studies the relationship between market sentiment and:
- Trader profitability
- Trading behavior
- Risk-taking patterns

The goal is to extract actionable insights and strategy recommendations using real trading data.

---

## Data


- `historical_data.csv`  
  Trader-level transaction data (timestamps, trade size, direction, PnL).
 Due to GitHub file size limits, the full historical trade dataset is not included.  
A sample dataset is provided (`historical_data_sample.csv`) for reproducibility. Full data can be requested if needed.



- `fear_greed_index.csv`  
  Daily market sentiment labels (Fear / Greed).

---

## Methodology

- Aggregate trades at **daily, per-account** level
- Align trading data with daily sentiment
- Compute key metrics:
  - Daily PnL
  - Trades per day
  - Average trade size
  - Long/short ratio
- Segment traders by:
  - Trading frequency
  - Position size
  - PnL consistency
- Compare performance and behavior across sentiment regimes
- Optional: simple predictive model for next-day profitability

---
## Outputs (Preview)

The `outputs/` folder contains:
- ` [performance_by_sentiment.csv](https://github.com/user-attachments/files/25074346/performance_by_sentiment.csv)  — summary table of PnL by sentiment
- [segment_comparison.csv](https://github.com/user-attachments/files/25074329/segment_comparison.csv)  — analysis across trader segments
- `<img width="878" height="585" alt="pnl_distribution_by_sentiment" src="https://github.com/user-attachments/assets/b8d27919-a208-4ce5-a58f-88564a1492e4" /> — PnL distribution chart
- `<img width="1022" height="666" alt="trade_frequency_by_sentiment" src="https://github.com/user-attachments/assets/c7d7de3e-5c70-4858-88e1-102a1bf19a75" /> — trade frequency chart


---
### Bonus: Predictive Modeling

A simple predictive model using logistic regression was included to estimate next-day profitability based on sentiment and behavior features.  
The section explains model performance, class imbalance, and limitations.

---



