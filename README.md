---

# 📈 Stock Market Forecasting using Facebook Prophet

This mini project demonstrates time series forecasting of Tesla's stock prices using the **Facebook Prophet** library. It serves as a practical example of applying predictive analytics and time series modeling on real-world financial data.

> 🧠 **Goal**: To forecast Tesla (TSLA) stock prices using Prophet and evaluate trends, seasonality, and volatility based on historical closing prices.

---

## 📌 Table of Contents

- [Introduction](#introduction)
- [Libraries Used](#libraries-used)
- [Data Overview](#data-overview)
- [Analysis Performed](#analysis-performed)
- [Prophet Forecasting](#prophet-forecasting)
- [Key Insights](#key-insights)
- [How to Run](#how-to-run)
- [Conclusion](#conclusion)

---

## 📖 Introduction

Stock prices are inherently volatile and influenced by numerous market dynamics. This project focuses on understanding and forecasting the closing prices of Tesla Inc. using **Facebook Prophet**, an open-source forecasting tool developed by Meta.

Prophet is well-suited for time series data with clear trends and seasonality, and is robust to missing data and outliers.

---

## 🛠 Libraries Used

- `pandas` – Data manipulation and preprocessing  
- `matplotlib` – Visualization  
- `seaborn` – Enhanced visualization  
- `Prophet` – Time series forecasting  
- `numpy` – Numerical operations  

---

## 📊 Data Overview

The dataset used contains historical stock prices of **Tesla Inc.**, specifically focusing on:

- `Date` — Trading date  
- `Close` — Closing stock price  

The data was processed to suit Prophet's input requirements:
- `ds`: datetime column
- `y`: target column (closing price)

---

## 📈 Analysis Performed

### 🔹 1. **Moving Average Analysis**
- **MA10** (10-day moving average): Captures short-term trends
- **MA50** (50-day moving average): Highlights long-term movement
- Identified potential **bullish and bearish crossovers** for trade signals.

### 🔹 2. **Return Analysis**
- Computed **daily returns** to measure price fluctuations
- Visualized **volatility periods** and notable spikes
- Interpreted high-volatility periods possibly driven by external events

---

## 🔮 Prophet Forecasting

- Formatted the data into `ds` and `y` columns
- Trained Prophet on the historical stock data
- Forecasted future closing prices for a defined period
- Visualized forecast results along with **trend** and **seasonality components**

---

## 📌 Key Insights

- Tesla’s stock showed a **long-term upward trend** with intermittent corrections.
- **Moving averages** revealed momentum changes and trend reversals.
- **Daily return analysis** highlighted volatility and potential risk.
- Prophet successfully modeled the stock's **trend** and **weekly/yearly seasonality**.

---

## ▶️ How to Run

1. Clone the repository or download the notebook.
2. Install the required libraries:
   ```bash
   pip install pandas matplotlib seaborn prophet
```

3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook Stock\ Market\ Forecasting\ using\ Prophet.ipynb
   ```

---

## ✅ Conclusion

This mini-project demonstrates a clear and applied understanding of:

* Time series preprocessing and transformation
* Trend and volatility analysis through financial indicators
* Using Facebook Prophet for forecasting real-world stock data

While simplified for demonstration purposes, this project showcases my comfort with **forecasting workflows**, **financial data**, and **interpreting model results** — all key skills in data science and analytics roles.

---

## 📎 Note

This is a minimal implementation focused on concept demonstration. For production-grade forecasting, additional steps such as model evaluation, hyperparameter tuning, and inclusion of external regressors would be considered.

---

## 🧑‍💻 Author

**Rasika Gautam**
*Data Science & AI Enthusiast* | B.Tech MAC, NSUT
[GitHub](https://github.com/rasika1205)

