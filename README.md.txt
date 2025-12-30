# Trader Behavior Analysis Under Market Sentiment Regimes

## Objective
This project analyzes how trader behavior and performance vary across different market sentiment conditions using the Bitcoin Fear & Greed Index. By combining historical trade-level data with daily sentiment classifications, the analysis uncovers behavioral patterns related to profitability, risk-taking, and trading direction.

## Problem Statement
Cryptocurrency markets are highly driven by investor emotions such as fear and greed. Understanding how these emotions impact trading behavior can help improve risk management and trading strategies. This project explores the relationship between market sentiment and trader performance.

## Datasets Used
1. **Historical Trader Data (Hyperliquid)**  
   - Trade-level execution data including price, size, direction, timestamps, and closed PnL.

2. **Bitcoin Fear & Greed Index**  
   - Daily market sentiment classification ranging from Extreme Fear to Extreme Greed.

## Methodology
- Data cleaning and preprocessing
- Timestamp standardization and date extraction
- Merging trading data with sentiment data using date
- Exploratory Data Analysis (EDA)
- Visualization of sentiment-based behavioral patterns

## Key Insights
- Trade-level profitability improves during Greed and Extreme Greed periods.
- Fear periods generate higher total profits primarily due to increased trading volume.
- Traders take larger position sizes during Fear, indicating opportunistic or contrarian behavior.
- Extreme sentiment conditions exhibit higher profit and loss volatility.
- Buy and sell activity remains largely balanced, with increased selling during Extreme Greed.

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Google Colab

## Project Structure
ds_mritunjay_singh/
├── notebook_1.ipynb
├── ds_report.pdf
├── README.md
├── csv_files/
│ └── merged_data.csv
└── outputs/
├── pnl_vs_sentiment.png
└── trade_size_vs_sentiment.png

## Google Colab Notebook
Access the complete analysis notebook here:  
https://colab.research.google.com/drive/1Bh3VYwVfAyFNXD5zVwzIcmAZJOjvW0IE?usp=sharing

## Results
The analysis demonstrates that market sentiment is strongly associated with changes in trader behavior and performance. While Fear-driven markets encourage higher participation and larger trades, Greed-driven markets provide better trade-level efficiency and win rates.

## Conclusion
Market sentiment serves as a valuable contextual indicator rather than a standalone trading signal. Incorporating sentiment awareness into trading decisions can enhance risk management and improve overall trading performance in volatile cryptocurrency markets.

