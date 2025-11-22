# 📈 Stock Trend Predictor
**Stock Movement Forecasting for Strategic Investment Optimization**

This project implements a complete machine-learning and deep learning pipeline for predicting **stock price direction**, built specifically using **Tesla (TSLA)** and **NVIDIA (NVDA)** historical market data.  
It includes XGBoost models, LSTM sequence models, engineered features, and an interactive Streamlit app for real-time inference.

## 🧠 Project Summary
The Stock Trend Predictor analyzes historical closing prices, volatility, and engineered technical indicators from TSLA and NVDA.  
These two tickers were used for the datasets, feature engineering, XGBoost training, LSTM training, and deployment.

## 📂 Repository Contents
- Jupyter notebook with the full workflow  
- Streamlit app (`app.py`)  
- Trained TSLA & NVDA models  
- Feature dataset `TSLA_NVDA_SP_Featured.csv`  
- Scalers and model artifacts  

## ✔ Key Features
- TSLA & NVDA-only forecasting
- XGBoost + LSTM models
- Technical indicators
- Streamlit predictor
- Deployment-ready artifacts

## 🛠 Installation
```
pip install -r requirements.txt
```

## 🔍 Prediction Workflow
1. Choose either TSLA or NVDA  
2. Load model + scaler for that stock  
3. Display predicted movement: Up, Down, Neutral  

## 📘 Full Notebook
The notebook contains:
- Data cleaning  
- Feature engineering  
- LSTM modeling  
- XGBoost modeling  
- Evaluation and export  

## 📌 Future Enhancements
- Add more tickers  
- Add sentiment analysis  
- Deploy via API  
- Model ensembling
