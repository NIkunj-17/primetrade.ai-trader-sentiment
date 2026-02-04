# Trader Performance vs Market Sentiment

## Overview
This project analyzes how Bitcoin market sentiment (Fear/Greed) affects trader behavior and performance on the Hyperliquid platform. The goal is to derive simple, actionable, sentiment-aware trading insights.

## Data Used
- **Market Sentiment**: Daily Fear/Greed classification
- **Trader Data**: Trade-level Hyperliquid data (PnL, trade size, frequency, leverage)

## What Was Done
- Converted trade-level data into daily trader metrics
- Merged trader data with daily sentiment
- Compared performance across sentiment regimes
- Segmented traders by activity and consistency

## Key Outcome
Fear regimes show higher profitability and consistency, while Extreme Greed regimes are riskier for most traders.

## ⚙️ Setup
1. Clone this repo.
2. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn`
3. Run the Jupyter notebook in the `notebooks/` folder.
