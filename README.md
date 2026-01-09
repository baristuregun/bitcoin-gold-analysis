# Analyzing Bitcoin and Gold Market Dynamics  
*DSA 210 – Term Project*

# Research Question  
Is Bitcoin beginning to behave like a store of value similar to gold when examined through volatility, returns, and correlation over time?

# Project Overview  
This project analyzes Bitcoin and gold from a financial perspective by comparing their price behavior, volatility, and risk adjusted performance. Gold has a long history as a stable store of value, while Bitcoin is a newer digital asset known for sharp price swings. Using time series analysis, the study examines whether Bitcoin is developing characteristics associated with gold or if it continues to function mainly as a high-risk speculative asset.

# Motivation  
The idea of Bitcoin as “digital gold” is widely discussed but often lacks quantitative support. Gold maintains value during uncertainty due to its stability and low volatility. Bitcoin, however, shows extreme price movement yet is increasingly adopted by investors.  
This project aims to evaluate the “digital gold” argument using data by analyzing historical returns, log returns, volatility patterns, and correlations. The goal is to provide objective insight rather than rely on assumptions or market narratives.

# Hypotheses  

# 1. Volatility Comparison  
- H₀: Bitcoin and gold have similar average volatility.  
- H₁: Bitcoin has significantly higher volatility than gold.

# 2. Correlation Over Time  
- H₀: The correlation between Bitcoin and gold returns does not change over time.  
- H₁: The correlation between Bitcoin and gold returns increases over time.

# 3. Return Differences  
- H₀: The mean daily returns of Bitcoin and gold are statistically similar.  
- H₁: The mean daily returns of Bitcoin and gold differ significantly.

# Data Sources  
- *Yahoo Finance API:* Historical gold prices (XAU-USD)  

# Analysis Plan  
- Collect historical daily closing prices for Bitcoin and gold  
- Clean and align both datasets by date  
- Calculate daily returns, log returns, cumulative returns, and rolling volatility  
- Plot price movements on linear and logarithmic scales  
- Compute rolling correlations between Bitcoin and gold  
- Conduct hypothesis testing using appropriate statistical methods (t-tests, variance tests, correlation analysis)

# Tools  
- Python  
- Jupyter Notebook  
- pandas, numpy  
- matplotlib, seaborn  
- yfinance API, CoinGecko API  

# Expected Outcomes  
- Bitcoin will likely show higher returns but significantly more volatility compared to gold  
- Gold is expected to remain more stable as a store of value  
- Bitcoin may show signs of maturing over time, such as reduced volatility or a stronger relationship with gold  

# Phase 2 – Exploratory Data Analysis Findings
The exploratory data analysis shows that Bitcoin is significantly more volatile than gold
throughout the observed period. Rolling volatility analysis highlights the higher risk
associated with Bitcoin, while gold remains relatively stable. Additionally, rolling
correlation results indicate that the relationship between Bitcoin and gold is unstable
and fluctuates around zero, suggesting that Bitcoin does not consistently behave like gold
as a store of value.

# Phase 3 – Machine Learning
Machine learning models were applied to predict next day Bitcoin volatility  
(30-day rolling volatility) using lagged returns and volatility features from Bitcoin and gold.
A persistence baseline and Linear Regression achieved strong performance (R² ≈ 0.968),  
while Random Forest performed worse. Feature importance indicates that Bitcoin’s own volatility is the dominant predictor,  
and gold-related features contribute little in this setup.
