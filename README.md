# Market Sentiment & Trader Behavior Analysis

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
  A small sample dataset is included for reproducibility. Full data can be provided upon request.


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



---

## How to Run

```bash
pip install pandas numpy matplotlib scikit-learn
notebook/data_science_internship.ipynb


## Key Outputs

Performance comparison across Fear vs Greed regimes
Trader behavior analysis by segment
Visualizations of PnL distribution and trade frequency
Strategy recommendations based on sentiment

