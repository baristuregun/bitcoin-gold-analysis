# Dsa 210 Project 

Analyzing Bitcoin and Gold Market Dynamics

# Project Overview  
This project examines Bitcoin and gold to understand how each functions as a store of value. Gold is a long-established and relatively stable asset, whereas Bitcoin is modern, digital, and significantly more volatile. The analysis will focus on their price movements, volatility, and long-term behavior to evaluate whether Bitcoin is beginning to exhibit characteristics similar to gold.

# Motivation  
Bitcoin is popularly referred to as “digital gold,” though this reinforces belief more than evidence. Gold has been a proven safe-haven asset for centuries, while Bitcoin—despite its risks—has started attracting institutional investors and is sometimes treated as a hedge asset.  
By comparing the two using metrics like returns, volatility, and rolling correlation, this study aims to determine whether Bitcoin is becoming more like gold or still behaves chiefly as a speculative asset.

# Data Sources  
- Bitcoin → Daily historical prices from CoinGecko API or Yahoo Finance  
- Gold  → Daily historical prices from Yahoo Finance  
Both datasets will be synchronized by date.

# Methodology  
- Gather daily closing prices for Bitcoin and gold  
- Clean and align the data  
- Compute daily and cumulative returns, and rolling volatility  
- Plot long-term and log-scale price trends  
- Analyze rolling correlation over time (early vs. recent Bitcoin behavior)

# Tools
- Python, Jupyter Notebook, pandas, matplotlib, seaborn, yfinance or CoinGecko API.

# Expected Findings  
- Bitcoin will likely have higher returns but significantly higher volatility than gold  
- Gold should maintain its stability  
- Bitcoin may show signs of maturity over time (e.g., reduced volatility, stronger correlation with gold)  
This project does not aim to predict future prices — it focuses on historical analysis and interpretation.

# 7. Timeline (Based on Course Deadlines)  
| Phase   | Task                           | Deadline      |
|---------|--------------------------------|---------------|
| Phase 1 | Proposal submission            | 31 Oct 2025   |
| Phase 2 | Data collection & EDA          | End of Nov 2025 |
| Phase 3 | Analysis & interpretation       | Early Jan 2026 |
| Final   | Report & notebook submission    | 9 Jan 2026    |

