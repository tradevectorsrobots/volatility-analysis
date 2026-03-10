# volatility-analysis\
\
Historical volatility analysis and modeling for stocks - multiple datasets and analytical notebooks by Trade Vectors LLP\
\
## Project Structure\
\
- `Notebooks/`: Contains Jupyter notebooks with various volatility analysis techniques.\
- `USStocks/`: Contains historical price data for US stocks in CSV format.\
\
## Notebook Versions\
\
| Version | File | Description |\
|---------|------|-------------|\
| **v1** | `volatility_analysis_v1.ipynb` | **Basic Volatility Metrics**: Calculates Historical Volatility (HV), Standard Deviation, ATR, and Parkinson Volatility. Includes multi-stock comparison visualizations. |\
| **v2** | `volatility_analysis_v2.ipynb` | **Advanced Modeling (GARCH)**: Implements GARCH(1,1), EGARCH, and GJR-GARCH models for volatility forecasting. Focuses on volatility clustering and persistence analysis. |\
| **v3** | `volatility_analysis_v3.ipynb` | **Risk & Performance**: Focuses on risk management including Value at Risk (VaR), Expected Shortfall (ES), Maximum Drawdown, and Sharpe/Sortino ratios. |\
\
## Data Source\
\
Historical stock price data is sourced from provided CSV files in the `USStocks` folder, covering major tickers like NVDA, AAPL, MSFT, AMZN, and IBM.\
\
## Author\
Trade Vectors LLP, Mumbai
