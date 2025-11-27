# Trader Behavior vs Market Sentiment Analysis

This project examines how trading activity, trading volume, and profit change under different market sentiment levels: Fear, Neutral, Greed, and Extreme Greed.

## Datasets

- `historical_data.csv` — 211,224 raw trades  
- `fear_greed_index.csv` — daily Fear–Greed Index

## Objective

Understand how trader behavior (trades, volume, profit) reacts to market sentiment and identify patterns useful for trading strategies and risk management.

## Workflow

1. Load both datasets (Pandas / Google Colab).  
2. Convert timestamps to datetime and extract `date`.  
3. Aggregate raw trades into daily metrics: total trades, total volume (USD), average execution price, total PnL.  
4. Merge daily trading metrics with daily Fear–Greed sentiment via `date`.  
5. Perform EDA and create visualizations.

## Visualizations

All images are stored in `ds_sheraj_sharif/outputs/`.

### Correlation Heatmap
Shows correlation between trading metrics and sentiment.  
`ds_sheraj_sharif/outputs/download (5).png`  
![Correlation Heatmap](ds_sheraj_sharif/outputs/download(5).png)

### Sentiment vs Total Trades
Shows how trading activity changes with sentiment.  
`ds_sheraj_sharif/outputs/download (6).png`  
![Sentiment vs Total Trades](ds_sheraj_sharif/outputs/download(6).png)

### Sentiment vs Profit/Loss
Shows how daily profit varies with sentiment.  
`ds_sheraj_sharif/outputs/download (7).png`  
![Sentiment vs PnL](ds_sheraj_sharif/outputs/download(7).png)

### Fear vs Greed Bar Chart
Compares activity across sentiment categories.  
`ds_sheraj_sharif/outputs/download (8).png`  
![Fear vs Greed Bar Chart](ds_sheraj_sharif/outputs/download(8).png)

## Key Findings

- Trading activity is highest during **Fear** (low sentiment).  
- Profitability peaks on fearful days — volatility produces opportunities.  
- Greedy or calm markets show lower trading activity and lower profit.  
- Higher trading volume is strongly associated with higher profit.

## Conclusion

Even with only seven trading days in the dataset, the analysis shows a clear pattern: traders increase activity and profitability during fearful market conditions and reduce activity during greedy or stable periods. Market sentiment has a notable influence on trader behavior.


