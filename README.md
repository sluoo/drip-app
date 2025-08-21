# 💧 DRIP Calculator App

Goal is to create a lightweight Streamlit app that fetches the latest stock price and dividend information from Yahoo Finance and calculates how many shares you need to qualify for a DRIP (Dividend Reinvestment Plan). Supports both fractional and whole-share DRIPs.

---

## 🧮 Features

- Pulls real-time stock price and dividend data using Yahoo Finance
- Calculates:
  - Next dividend payout based on your holdings
  - Minimum shares needed for a whole-share DRIP
  - Expected fractional shares (if supported)
- What-if simulator with a share slider
- Price + dividend history chart
- Toggle to exclude special dividends

---

## 🚀 Built With

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [yfinance](https://pypi.org/project/yfinance/)
- [pandas](https://pandas.pydata.org/)

---

## 📦 Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/sluoo/drip-app.git
   cd drip-app
