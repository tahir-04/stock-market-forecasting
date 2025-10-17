# 📈 Stock Market Time Series Forecasting using ARIMA, SARIMA, Prophet & LSTM

This project demonstrates **end-to-end stock price forecasting** using classical statistical models (ARIMA, SARIMA, Prophet) and a **deep learning approach (LSTM)**.  
It focuses on Coca-Cola (KO) stock from 2018–2024, using **Python, yFinance, and TensorFlow** for analysis and prediction.

---

## 🚀 Features
- 📊 Real-time stock data fetched via Yahoo Finance (yFinance)
- 🔍 Time series pre-processing, visualization, and trend analysis
- 🧠 Implementation of:
  - ARIMA for linear patterns
  - SARIMA for seasonality
  - Prophet for flexible trend forecasting
  - LSTM for deep learning-based sequential predictions
- 📈 Model comparison using RMSE, MAE, and MAPE
- 🏆 Automatic best-model selection based on RMSE

---

## 🧰 Tech Stack
- **Languages:** Python
- **Libraries:** yfinance, pandas, numpy, matplotlib, statsmodels, prophet, tensorflow, scikit-learn
- **Tools:** Jupyter Notebook / Google Colab

---

## 📊 Visual Outputs
Example forecasts from each model:

![Forecast Comparison](results/plots/model_comparison.png)
![LSTM Forecast](results/plots/lstm_forecast.png)

---

## ⚙️ Installation

```bash
# Clone this repository
git clone https://github.com/yourusername/stock-market-forecasting.git

# Navigate to project directory
cd stock-market-forecasting

# Install dependencies
pip install -r requirements.txt
