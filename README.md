
# 📈 Stock Analysis & Prediction

A comprehensive **Stock Market Analysis and Prediction Project** built using **Python**, **Machine Learning**, and **Deep Learning**.
This project is designed to **analyze historical stock data**, visualize trends, and predict stock prices using **Linear Regression** and **LSTM**.

> **Note:** This project uses **historical stock data** and predictions are **trend indicators**, not exact prices.

---

## 🚀 Features

* Download and analyze **historical stock data** from Yahoo Finance
* Visualizations:

  * Line plots of closing prices
  * Candlestick charts for daily trends
* Technical Indicators:

  * **Moving Averages (MA20 & MA50)** for trend detection
  * **RSI (Relative Strength Index)** for overbought/oversold signals
* Predict stock prices using:

  * **Linear Regression** (baseline)
  * **LSTM Neural Network** (advanced sequential prediction)
* Evaluate model performance using **RMSE**
* Compare **predicted vs actual prices** visually

---

## 🛠️ Tech Stack

* **Python 3.x**
* **Jupyter Notebook**
* Libraries:

  * `numpy`, `pandas`
  * `matplotlib`, `seaborn`, `plotly`
  * `yfinance`
  * `scikit-learn`
  * `tensorflow`

---

## 📂 Project Structure

```
│── Stock_Analysis_Prediction.ipynb  # Main notebook
│── README.md                        # Project description
│── License                          # License
```


---

## 🎯 How to Use

1. Clone the repository:

```bash
git clone https://github.com/Mani-doliya/Stock-Analysis-Prediction.git
```

2. Install required Python libraries:

```bash
pip install numpy pandas matplotlib seaborn plotly yfinance scikit-learn tensorflow
```

3. Open `Stock_Analysis_Prediction.ipynb` in **Jupyter Notebook**.
4. Change the stock ticker symbol to analyze a different stock:

```python
ticker = "AAPL"  # Replace with any stock symbol
```

5. Run all notebook cells sequentially to:

   * Visualize stock trends
   * Compute technical indicators
   * Predict stock prices using Linear Regression and LSTM

---

## 📈 Insights & Conclusion

* **LSTM captures sequential trends** better than Linear Regression.
* Predictions act as **trend indicators**, not exact prices.
* Technical indicators provide insights into **market behavior and potential trading signals**.
* Demonstrates **full workflow**: data collection → analysis → technical indicators → prediction → evaluation.

---

## 📝 Author

**Manish Doliya** 

---

## 📄 License

This project is open-source under the **MIT License**.

---
