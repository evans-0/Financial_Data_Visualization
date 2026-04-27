# Financial Data Visualization 📊

A collection of interactive financial data visualizations focused on the **Indian stock market (NSE)** and **mutual funds**, built with Python.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 📁 Structure

```
Financial_Data_Visualization/
├── candle.py     # Interactive candlestick chart app — 10 NSE stocks
├── MF.ipynb      # Indian mutual funds analysis & visualization
└── README.md
```

---

## 📄 Projects

### 🕯️ Candlestick Chart App — `candle.py`

An interactive desktop app that fetches **10 years of live OHLC data** from Yahoo Finance and renders a professional candlestick chart with a range slider — all with a dropdown selector and a single button click.

**How it works:**
1. Select a stock from the dropdown
2. Click **Show Plot** — the chart opens in the browser

**Stocks available:**

| Ticker | Company |
|--------|---------|
| `ITC.NS` | ITC Limited |
| `RELIANCE.NS` | Reliance Industries |
| `TITAN.NS` | Titan Company |
| `TCS.NS` | Tata Consultancy Services |
| `BHARTIARTL.NS` | Bharti Airtel |
| `TRENT.NS` | Trent Limited |
| `LT.NS` | Larsen & Toubro |
| `HINDUNILVR.NS` | Hindustan Unilever |
| `HDFCBANK.NS` | HDFC Bank |
| `SBIN.NS` | State Bank of India |

**Tech used:**
- `yfinance` — fetches 10Y historical OHLC data live
- `plotly` — interactive candlestick chart with range slider
- `nicegui` — lightweight UI with dropdown + button
- `pandas` / `numpy` — data handling

---

### 📈 Mutual Funds Analysis — `MF.ipynb`

A Jupyter notebook exploring and visualising Indian mutual fund data.

---

## 🚀 Getting Started

```bash
git clone https://github.com/evans-0/Financial_Data_Visualization.git
cd Financial_Data_Visualization

pip install pandas numpy plotly yfinance nicegui

# Run the candlestick app
python candle.py

# Open the mutual funds notebook
jupyter notebook MF.ipynb
```

---

## ⚖️ License

This project is licensed under the [MIT License](./LICENSE).
