# Market Trend & Anomaly Detection Pipeline

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)  
*Automated financial data pipeline designed to ingest, process, analyze, and visualize equity market momentum and technical anomalies.*

---

## 📌 Overview
Configured and implemented an automated financial data ingestion pipeline using Python and financial APIs to process market trends and technical metrics. Applied algorithmic and data analysis concepts—including simple and exponential moving averages, relative strength index (RSI)—to enable real-time detection of price anomalies and deliver visual breakout analysis for target equity instruments.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Processing & Manipulation:** Pandas
* **Financial Data API:** `yfinance`
* **Data Visualization:** Matplotlib
* **Environment:** Google Colab

---

## ✨ Key Features
* **Automated Data Ingestion:** Pulls historical daily time-series data (OHLCV) for target tickers using financial data APIs.
* **Technical Indicator Calculations:** Computes 20-day Simple Moving Average (SMA) and 14-day Relative Strength Index (RSI) dynamically via Pandas.
* **Signal Classification:** Automatically flags bullish breakouts, overbought risks, and oversold conditions.
* **Visual Rendering:** Generates clean, dual-axis Matplotlib trend charts displaying price action against moving average baselines.

---

## 🚀 How to Run
1. Click the **"Open in Colab"** badge above (or upload the notebook to your own Google Colab session).
2. Run **Cell 1** to install dependencies (`yfinance`, `pandas`, `matplotlib`).
3. Run **Cell 2** to execute the pipeline, view the generated technical charts, and output the summary data frame.
