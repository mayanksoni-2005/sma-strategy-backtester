# 📈 SMA Strategy Backtester

This is a **Streamlit web application** that allows users to backtest a Simple Moving Average (SMA) crossover strategy on historical stock data using Yahoo Finance.

## 🚀 Features

- Fetch historical stock data using `yfinance`
- Apply an SMA crossover strategy with adjustable short and long windows
- Visualize:
  - Cumulative returns (Buy & Hold vs Strategy)
  - Buy/Sell signals on price chart
  - Portfolio value over time
- Compute key performance metrics:
  - ✅ **Sharpe Ratio** – Measures risk-adjusted returns
  - 📉 **Maximum Drawdown** – Captures the worst peak-to-trough decline
- Interactive UI built with Streamlit for live tweaking of parameters

## 🛠️ Tech Stack

- Python 3
- [Streamlit](https://streamlit.io/)
- [yfinance](https://pypi.org/project/yfinance/)
- pandas, numpy, matplotlib

## 📦 Installation (Local)

```bash
git clone https://github.com/your-username/sma-strategy-backtester.git
cd sma-strategy-backtester
pip install -r requirements.txt
streamlit run app.py
