# Trader Performance vs Market Sentiment — Summary

## Objective
The goal of this analysis is to understand how market sentiment (Fear vs Greed) influences trader behavior and performance on the Hyperliquid platform.

## Data Preparation
- Loaded Bitcoin Fear & Greed Index data and Hyperliquid trader data
- Cleaned missing values and aligned both datasets at daily level
- Created key metrics such as daily PnL, win rate, trade count, and position behavior

## Key Findings
1. Trader performance is higher during Greed and Extreme Greed days, with higher average PnL and win rates.
2. Fear periods show reduced trade frequency but higher variability in trade sizes, indicating riskier behavior by some traders.
3. Active and consistent traders perform more reliably across sentiment regimes compared to infrequent traders.

## Trader Segmentation
- Frequent vs Infrequent traders
- Consistent winners vs Inconsistent traders
- High-risk vs Low-risk traders (based on trade size)

## Actionable Strategies
1. During Fear days, reduce leverage and trade size to manage downside risk.
2. During Greed days, active traders can increase participation with controlled position sizing.

## Bonus Modeling
A simple Logistic Regression model was built to predict whether the next trading day would be profitable based on sentiment and recent trading behavior. The model demonstrates strong predictive signal and is intended as a proof of concept.
