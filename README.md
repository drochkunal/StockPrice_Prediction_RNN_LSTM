# StockPrice_Prediction_RNN_LSTM
# 📈 Stock Price Prediction using LSTM (PyTorch)

## 📌 Project Overview

This project focuses on building a deep learning model to predict stock prices using historical market data. The model leverages **Long Short-Term Memory (LSTM)** networks to capture temporal dependencies in financial time-series data.

The objective is to apply time-series preprocessing, sequence modeling, and deep learning techniques to accurately forecast stock price trends.

---

## 📊 Dataset Description

The dataset contains historical stock data with multiple features such as:

* Open price
* High price
* Low price
* Close price
* Trading Volume

👉 These features provide insights into market behavior and trends over time.

---

## ⚙️ Project Workflow

### 1. Data Preprocessing

* Filtered data for a specific stock (e.g., AAPL)
* Sorted data chronologically
* Applied **MinMax Scaling** to normalize values
* Split data into training (80%) and testing (20%)

---

### 2. Sequence Creation

* Created sequences of **60 timesteps**
* Input: Past 60 days of stock data
* Output: Next day closing price

---

### 3. Model Building

Implemented an LSTM-based neural network using PyTorch:

* LSTM layer with 100 hidden units
* Dropout for regularization
* Fully connected layer for final prediction

---

### 4. Model Training

* Used **Mean Squared Error (MSE)** as loss function
* Optimized using **Adam optimizer**
* Trained over multiple epochs with mini-batch learning

---

### 5. Model Evaluation

* Evaluated performance using **Root Mean Squared Error (RMSE)**
* Visualized predictions vs actual prices

---

## 🚀 Results

* Achieved RMSE: **4.33**
* Model successfully captured **trend and temporal patterns**
* Predictions closely follow actual stock movements with slight smoothing

---

## 🛠️ Tech Stack

* Python 🐍
* PyTorch
* Pandas & NumPy
* Scikit-learn
* Matplotlib

---

## 📈 Key Learnings

* Importance of proper **time-series preprocessing**
* Handling **data leakage during scaling**
* LSTM’s ability to capture sequential dependencies
* Multi-feature input improves model performance

---

## 🔗 Future Improvements

* Add technical indicators (RSI, MACD)
* Compare LSTM with GRU and Transformer models
* Deploy using Streamlit or FastAPI
* Extend prediction to multi-step forecasting

---

## 👤 Author

**Kunal Droch**
