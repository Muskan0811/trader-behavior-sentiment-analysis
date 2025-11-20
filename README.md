Trader Behavior vs Market Sentiment — Overview

This project explores how trader performance on Hyperliquid changes across different market sentiment states such as Fear, Extreme Fear, Greed, and Extreme Greed. The idea was to understand whether emotions in the wider market influence how traders behave, how actively they trade, and how profitable they are.

What the project covers

Cleaning and preparing two datasets:

Hyperliquid historical trader data

Bitcoin Fear–Greed Index

Converting timestamps and aligning both datasets by date

Creating simple daily metrics: average PnL, win rate, and number of trades

Comparing these metrics across different sentiment categories

Summarizing the patterns that appear

Key observations

Traders trade the most during Fear and Extreme Fear, but their average PnL is lowest on these days.

During Greed and Extreme Greed, traders trade less but earn more, and profit per winning trade tends to be higher.

Win rate stays fairly stable across all sentiment types.

Neutral sentiment days show unusually high PnL because of a few large outlier trades.

Overall, trader activity appears more emotional and reactive during fear-driven markets.

Files included

trader_behavior_sentiment_analysis.ipynb – the complete analysis performed in Google Colab.

Tools used

Python

Pandas

Matplotlib

Google Colab
