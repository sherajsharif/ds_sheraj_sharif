Trader Behavior vs Market Sentiment Analysis

This project examines how trading activity, volume, and profit change under different market sentiment levels: Fear, Neutral, Greed, and Extreme Greed.

Datasets

historical_data.csv – 211,224 raw trades

fear_greed_index.csv – Daily market sentiment values

Objective

To understand how trader behavior reacts to market sentiment and identify patterns between:

Trading activity

Trading volume

Profit/Loss

Sentiment levels

Workflow

Load both datasets

Convert timestamps and extract date

Aggregate daily trading metrics

Merge trading data with sentiment data

Perform exploratory data analysis and create visualizations

Visualizations
1. Correlation Heatmap

2. Sentiment vs Total Trades

3. Sentiment vs Profit/Loss

4. Volume vs Profit/Loss

5. Fear vs Greed Bar Chart

Key Findings

Trading activity is highest during Fear

Profit is highest when sentiment is low

Greedy or calm markets show reduced trading activity

Higher trading volume is strongly linked to higher profit

Conclusion

Traders are more active and more profitable during fearful market conditions, while trading slows down during greedy or stable markets. Market sentiment has a clear influence on how traders behave.
