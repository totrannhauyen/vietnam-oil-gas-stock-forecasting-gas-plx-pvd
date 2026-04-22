# vietnam-oil-gas-stock-forecasting-gas-plx-pvd
Forecasting Vietnamese oil &amp; gas stock prices (GAS, PLX, PVD) using time series analysis and machine learning techniques.

## 📌 Overview
This project focuses on forecasting stock prices of Vietnamese oil & gas companies (GAS, PLX, PVD) using advanced deep learning architectures. It explores and compares multiple sequence models to capture temporal dependencies and complex patterns in financial time series data, with multi-horizon predictions for the next 30, 60, and 90 days.

## 🎯 Objectives
- Analyze historical stock price behavior
- Model time series dependencies using deep learning
- Perform multi-step forecasting (30 / 60 / 90 days ahead)
- Compare performance across multiple architectures
- Improve forecasting accuracy for financial data

## 🤖 Models Implemented
- GRU (Gated Recurrent Unit)
- LSTM (Long Short-Term Memory)
- CNN-LSTM (Hybrid Convolutional + Recurrent model)
- BiLSTM with Attention mechanism
- Transformer (Self-attention based model)

## 📊 Workflow
1. Data Collection & Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Model Training & Tuning  
5. Multi-horizon Forecasting (30 / 60 / 90 days)  
6. Evaluation & Comparison  

## 📈 Evaluation Metrics
- RMSE (Root Mean Squared Error)  
- MAE (Mean Absolute Error)  
- MAPE (%) – relative prediction error  
- DPA (%) – Directional Prediction Accuracy (correctly predicted price movement direction)

## 🛠️ Tech Stack
- Python (Pandas, NumPy)
- TensorFlow / PyTorch
- Scikit-learn
- Matplotlib / Seaborn

## 🚀 Key Highlights
- Comparative study of multiple deep learning models
- Multi-horizon forecasting (30, 60, 90 days ahead)
- Application of attention mechanisms in financial forecasting
- Exploration of Transformer architecture for time series
- Evaluation using both error-based and direction-based metrics (DPA)

## 🔮 Future Work
- Incorporate macroeconomic indicators (oil prices, CPI, etc.)
- Hyperparameter optimization
- Real-time forecasting pipeline
- Deploy forecasting system as a web application
