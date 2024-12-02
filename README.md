# Stock Price Prediction using Time Series Forecasting Transformer


## 📌 Project Overview

This project applies **time-series forecasting** techniques to predict monthly stock prices of companies listed on the National Stock Exchange (NSE) using historical data from 1990 to 2021. The core of the project is a **Transformer-based deep learning architecture** that captures long-term dependencies and trends in stock prices. The model leverages advanced **feature engineering** and **optimization** to deliver highly accurate predictions, aiding investors in making informed decisions.

---

## ✨ Features

- **Transformer-based Model**: Efficient handling of sequential data with self-attention mechanisms.  
- **LSTM Integration**: Comparison with LSTM for capturing sequential dependencies.  
- **Advanced Metrics**: Performance measured using MSE, MAPE, and R².  
- **Robust Preprocessing**: Missing data interpolation and normalization.  
- **Scalable Solution**: Applicable to portfolio optimization and risk management.

---

## 🚀 Technologies Used

- **Python**: Programming language.  
- **TensorFlow**: Deep learning framework.  
- **NumPy** and **Pandas**: Data manipulation and analysis.  
- **Matplotlib**: Visualization.  

---

## 📂 Project Architecture

1. **Data Collection**: Historical NSE stock data (1990–2021).  
2. **Data Preprocessing**:
   - Normalization using Min-Max Scaler.  
   - Linear interpolation for missing values.  
3. **Feature Engineering**:
   - Derived metrics like moving averages and volatility measures.  
4. **Model Training**:
   - Transformer and LSTM-based architectures.  
   - Optimized with Adam optimizer.  
5. **Evaluation**:
   - Metrics: MSE, MAPE, R².  
   - Training on an 80:20 train-test split.  

---

## 🛠 Installation & Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/arshiyaakishore/stock-price-prediction.git
   cd stock-price-prediction
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
3. **Run the Model**:
   ```bash
   python train_model.py

---

## 📊 Results

- **Transformer Model**:
  - R² Value: 0.9514  
  - RMSE: 1.7587  
  - MAE: 1.1597  


