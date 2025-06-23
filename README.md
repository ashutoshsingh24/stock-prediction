# 📈 Stock Price Prediction

This project predicts the next-day closing stock prices for Indian companies listed on the **NSE (National Stock Exchange)** using machine learning models. The approach combines historical stock data with technical indicators and trains both **Linear Regression** and **Random Forest Regressor** models to forecast prices accurately.

---

## 📊 Features

- ✅ Predicts **next-day closing prices** using past stock data
- 📉 Implements two models: **Linear Regression** & **Random Forest**
- 📈 Uses technical indicators:
  - 10-day & 50-day Moving Averages
  - Daily Percentage Return
  - Volume Change Percentage
- 📌 Visualizes:
  - Actual vs. Predicted prices
  - Correlation heatmap for feature selection

---

## 📦 Tech Stack

- Python 3.x
- Jupyter Notebook
- Libraries:
  - `yfinance`
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

---

## 📁 Project Structure

stock-price-prediction/
│
├── Stock_Prediction.ipynb # Main notebook with full code
├── README.md # Project documentation
├── requirements.txt # Python package dependencies


📊 Sample Output
📈 Model comparison: Linear vs Random Forest

📉 Mean Squared Error (MSE) for both models

🔥 Correlation heatmap of all technical indicators


📚 Use Cases
Financial forecasting

Time series modeling

Portfolio analysis

ML practice project in finance
