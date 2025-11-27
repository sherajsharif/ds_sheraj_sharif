Trader Behavior vs Market Sentiment Analysis

This project studies how trading behavior (activity, volume, and profitability) changes under different market sentiment conditions—Fear, Neutral, Greed, and Extreme Greed.

The analysis uses two datasets:

historical_data.csv — Raw trade data (211,224 trades)

fear_greed_index.csv —  Fear–Greed Index

📌 Objective

To explore the relationship between trader behavior and market sentiment, identify hidden trends, and understand whether traders act differently under Fear vs Greed.

This helps in:

Smarter trading strategies

Risk management decisions

Better market analysis

📂 Data Workflow
1. Data Loading

Loaded both CSV files using Pandas in Google Colab.

2. Timestamp Conversion

Converted timestamps into readable datetime and extracted date (sentiment is daily).

3. Daily Aggregation of Trading Data

From 211,224 raw trades, we computed:

Total trades per day

Total trading volume (USD)

Average execution price

Total Profit/Loss

The dataset contained trades for 7 unique dates.

4. Merge with Sentiment Data

Merged daily trading metrics with the Fear–Greed Index using the date column.

5. EDA (Exploratory Data Analysis)

Analyzed relationships between sentiment, trading volume, profit, and activity.

📈 Key Insights

Trader activity spikes during Fear — markets are volatile and active.

Profit is highest when sentiment is low — fear brings opportunities.

Greedy/Calm markets show lower trading activity — fewer price movements.

Volume strongly correlates with profit — more trading = more returns.


