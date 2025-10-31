# Analyzing Bitcoin and Gold Market Dynamics
**DSA 210 – Term Project**

# Project Overview  
This project compares Bitcoin and gold to understand how each functions as a store of value. Gold is a long-established, stable asset, while Bitcoin is digital, relatively new, and highly volatile. The goal is to examine whether Bitcoin is starting to behave like gold or if it still acts mainly as a speculative asset.

# Motivation  
Bitcoin is often called “digital gold,” but this idea is more cultural than analytical. Gold has served as a safe asset for centuries, whereas Bitcoin, despite its risks, has gained institutional interest.  
By analyzing returns, volatility, and rolling correlations between Bitcoin and gold, this project aims to evaluate whether Bitcoin is evolving into a store of value or remains primarily speculative.

# Data Sources  
- CoinGecko API: Historical Bitcoin price data (BTC-USD), market cap, volume  
- Yahoo Finance API: Historical gold prices (XAU-USD)  
Both assets will be aligned by date and analyzed over the same time periods.

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
This project focuses on historical analysis, not price prediction.



