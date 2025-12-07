# 📈 NASDAQ Historical Stock & ETF Price Dataset

This dataset contains **historical daily price data for all tickers currently trading on NASDAQ**.  
The up-to-date list of tickers is sourced from **nasdaqtrader.com**, and historical price data is retrieved from **Yahoo Finance** using the `yfinance` Python package.

The dataset includes price data **up to April 1, 2020**.  
If you need more recent data, you can **fork and re-run the data collection script available on Kaggle**.

---

## 📂 Dataset Structure

### `stocks/`
Contains historical daily price data for **individual NASDAQ-listed stocks**.  
Each file is named using its **ticker symbol** (e.g., `AAPL.csv`, `MSFT.csv`).

### `etfs/`
Contains historical daily price data for **Exchange-Traded Funds (ETFs)**.  
Each file is named using its corresponding **ETF ticker symbol**.

### `symbols_valid_meta.csv`
Contains **additional metadata for each ticker**, such as:
- Full company name
- Asset type
- Exchange information

---

## 📄 CSV File Format

| Column | Description |
|--------|-------------|
| Date | Trading date |
| Open | Opening price |
| High | Highest price during the day |
| Low | Lowest price during the day |
| Close | Closing price (adjusted for splits) |
| Adj Close | Adjusted close price (dividends & splits) |
| Volume | Number of shares traded during the day |

---

## 📅 Data Coverage

- **Start Date:** Varies by ticker  
- **End Date:** **April 1, 2020**

---

## 🛠 Data Source

- nasdaqtrader.com  
- Yahoo Finance  
- `yfinance` Python package  
- Kaggle

---

## ✅ Use Cases

- Stock price prediction
- Time series forecasting
- Algorithmic trading
- Machine learning & deep learning models
- Market analysis
- Financial research

---

## ⚠️ Disclaimer

This dataset is provided **for educational and research purposes only** and **not for financial advice**.

---

## 🚀 Updating the Dataset

1. Fork the Kaggle dataset.
2. Re-run the data collection script.
3. Fetch the latest prices from Yahoo Finance.


