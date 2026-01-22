# Trader Sentiment Analysis – Hyperliquid

This project explores the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using Hyperliquid historical data.

## 🧠 Objective

To determine whether market sentiment influences trader profitability and behavior.

## 📊 Methods

1. Loaded and cleaned:
   - Hyperliquid trading dataset
   - Bitcoin Fear & Greed Index
2. Normalized dates for both datasets
3. Merged datasets by date
4. Computed performance metrics:
   - Profit
   - Win rate
5. Visualized results using boxplots grouped by sentiment

## 📈 Key Findings

| Sentiment       | Avg Profit | Win Rate |
|----------------|-------------|-----------|
| Extreme Fear    | ~26         | ~36%      |
| Fear            | ~53         | ~48%      |
| Greed           | ~34         | ~38%      |
| Extreme Greed   | ~69         | ~47%      |
| Neutral         | ~41         | ~41%      |

- *Extreme Greed* shows the highest average profit.
- *Fear conditions* exhibit more disciplined trading with higher win rates.
- Profit distribution varies strongly with sentiment state.
- Sentiment appears to influence trader behavior and risk-taking.

## 📦 Files

- Trader_Sentiment_Analysis.ipynb – Full analysis
- profit_by_sentiment.png – Boxplot visualization
