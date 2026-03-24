# Analysis of the Impact of Sentiment on Stock Market Volatility
- Part of the Datathon organized by MUNI Digital Talent Lab
- Analysis of the relationship between sentiment indicators and S&P 500 daily volatility
- Goal was to assess whether sentiment indicators (Google SVI, Financial News sentiment, VIX index) **can help explain or predict market volatility**
- Data sources: Yahoo Finance (SPY, VIX), Google Trends SVI for 10 keywords, financial news headlines (FinBERT)
- Correlation analysis, Granger causality tests, OLS regression, and Elastic Net modeling
- **Best out-of-sample performer: Elastic Net**, keeping only few available feature
- Key finding: **simple "VIX-only" regression outperforms all multi-feature models**
