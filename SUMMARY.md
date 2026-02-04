# Summary: Market Sentiment & Trader Behavior Analysis

## Methodology

This project analyzes the relationship between market sentiment (Fear vs Greed) and trader behavior using two datasets: trader-level transaction data and a daily market sentiment index.

Trades were aggregated at a daily, per-account level and aligned with daily sentiment classifications. Key metrics such as daily PnL, trade frequency, average trade size, and long/short ratio were computed. Traders were further segmented based on activity level, position size, and PnL consistency to assess whether sentiment impacts different trader types differently.

An optional predictive modeling exercise was included to explore whether sentiment and behavioral features could help predict next-day trader profitability.

---

## Key Insights

1. **Trader performance differs across sentiment regimes**  
   Greed periods are associated with higher average profitability but also greater volatility, while Fear periods exhibit more conservative outcomes.

2. **Trading behavior responds to market sentiment**  
   Traders tend to increase trade frequency and position sizes during Greed regimes, indicating higher risk appetite.

3. **Sentiment effects vary by trader segment**  
   Consistent traders show more stable performance across regimes, whereas high-frequency and inconsistent traders experience larger performance swings.

---

## Strategy Recommendations

1. **Reduce risk during Fear regimes**  
   High-frequency and inconsistent traders should reduce trade frequency and position sizes during Fear periods to manage downside risk.

2. **Selective engagement during Greed regimes**  
   Consistent traders may cautiously increase activity during Greed periods to capture momentum, while maintaining disciplined risk controls.

---

## Notes on Bonus Analysis

A simple logistic regression model was built to predict next-day profitability using sentiment and behavioral features. While performance was constrained by class imbalance, the exercise highlights the importance of careful feature selection and realistic evaluation in financial prediction tasks.
