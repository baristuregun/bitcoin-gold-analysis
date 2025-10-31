# Analyzing Bitcoin and Gold Market Dynamics
**DSA 210 – Term Project**

# Project Overview  
This project analyzes Bitcoin and gold from a financial perspective by comparing their price behavior, volatility, and risk-adjusted performance. Gold has a long history as a stable store of value, while Bitcoin is a newer digital asset known for sharp price swings. By applying time-series techniques, the study aims to determine whether Bitcoin is gradually showing features similar to gold, such as long term value holding, lower volatility, or safe behavior, or if it still functions mainly as a speculative, high risk asset.

# Motivation  
The idea of Bitcoin being “digital gold” is widely discussed, but often without strong quantitative analysis. Gold is considered a safe asset because it maintains value during uncertainty, has relatively low volatility, and resists inflation. Bitcoin, on the other hand, has shown extreme price fluctuations but is increasingly being adopted by investors and financial institutions. This project is motivated by the need to test whether Bitcoin is evolving into a store of value or still behaves like a speculative asset. By examining historical returns, log returns, rolling volatility, and correlations, the study aims to provide objective evidence rather than rely on assumptions or media narratives.

# Data Sources  
- CoinGecko API: Historical Bitcoin price data (BTC-USD), market cap, volume  
- Yahoo Finance API: Historical gold prices (XAU-USD)  
(Both assets will be aligned by date and analyzed over the same time periods.)

## Supplementary Data:
- Google Trends – Public interest and search trends for “Bitcoin”, “gold”, “digital gold”, etc.  
- Crypto Fear & Greed Index (Alternative.me API)
  
# Analysis Plan 
- Collect historical daily closing prices for Bitcoin and gold.
- Clean and align the datasets.
- Calculate daily returns, cumulative returns, and rolling volatility.
- Plot price movements on both normal and log scales.
- Analyze how correlation changes over time (early Bitcoin vs. recent Bitcoin)

# Tools  
- Python, Jupyter Notebook, pandas, matplotlib, seaborn, yfinance API, CoinGecko API.

# Expected Outcomes  
- Bitcoin will likely have higher returns but much greater volatility than gold  
- Gold should remain more stable and consistent as a store of value  
- Over time, Bitcoin may show maturing behavior (decreasing volatility, stronger correlation with gold)  




