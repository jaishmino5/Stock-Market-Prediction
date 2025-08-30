# 📈 Stock Market Prediction using Moving Average & LSTM

This project focuses on predicting stock prices by combining **statistical techniques** (Moving Average) with a **deep learning approach** (LSTM).  
Data is sourced from **Yahoo Finance**, followed by **feature engineering** to enhance model performance.

---

## 🚀 Project Overview
- Collected historical stock market data from **Yahoo Finance**.
- Applied **feature engineering** to prepare data (scaling, lag features, rolling statistics).
- Implemented **Moving Average** for baseline trend prediction.
- Built an **LSTM (Long Short-Term Memory)** neural network for time-series forecasting.
- Compared results of statistical and deep learning models.

---

## 🛠️ Tech Stack
- **Python**
- **Pandas, NumPy** – Data preprocessing & feature engineering  
- **Matplotlib, Seaborn** – Visualization  
- **Yahoo Finance API** – Data collection  
- **TensorFlow / Keras** – LSTM implementation  
- **Scikit-learn** – Scaling & evaluation  

---

## 📊 Methodology
1. **Data Collection**: Downloaded historical stock data using Yahoo Finance.  
2. **Feature Engineering**:  
   - Created lag features  
   - Generated rolling means (moving averages)  
   - Normalized input values  
3. **Moving Average Model**: Predicted stock prices using simple and exponential moving averages.  
4. **LSTM Model**:  
   - Prepared time-series sequences  
   - Built & trained an LSTM model for forecasting future prices  
   - Tuned hyperparameters for accuracy  
5. **Evaluation**: Compared predictions against actual stock prices.  

---

## 📈 Results
- Moving Average gives a **baseline trend estimation**.  
- LSTM captures **temporal dependencies** and outperforms statistical methods in predicting future price movements.  
- Visualizations show how well the models fit stock price trends.  

---

## 📂 Project Structure
