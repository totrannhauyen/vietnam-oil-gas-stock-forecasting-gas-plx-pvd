# vietnam-oil-gas-stock-forecasting-gas-plx-pvd
Forecasting Vietnamese oil & gas stock prices (GAS, PLX, PVD) using advanced deep learning models.

---

## 📌 Overview
This project focuses on forecasting stock prices of major Vietnamese oil & gas companies, including GAS, PLX, and PVD, using advanced deep learning architectures. The study explores and compares multiple sequence models to capture temporal dependencies and complex patterns in financial time series data.

Stock price data is collected from financial platforms such as Investing.com and other Vietnamese stock data sources, then preprocessed and used to build predictive models. The project performs **multi-horizon forecasting** to predict stock prices for the next **30, 60, and 90 days**, providing insights into both short-term and medium-term market trends.

---

## 📊 Dataset Description

### 🔹 Data Source
- Data is collected using:
  - `yfinance` (Yahoo Finance API wrapper)
- Stocks:
  - GAS (PetroVietnam Gas)
  - PLX (Petrolimex)
  - PVD (PetroVietnam Drilling)

### 🔹 Dataset Structure
The dataset consists of historical daily trading data for each stock (GAS, PLX, PVD), including the following attributes:

| Feature | Description |
|--------|------------|
| `date` | Trading date |
| `close` | Closing price of the stock |
| `high` | Highest price during the trading session |
| `low` | Lowest price during the trading session |
| `open` | Opening price of the stock |
| `volume` | Number of shares traded |

### 🔹 Data Characteristics
- Time series data (chronologically ordered)
- Daily frequency
- May contain missing values (handled during preprocessing)
- Used for supervised learning with sliding window technique

---

## 🎯 Objectives
- Analyze historical stock price behavior
- Model time series dependencies using deep learning
- Perform multi-step forecasting (30 / 60 / 90 days ahead)
- Compare performance across multiple architectures
- Improve forecasting accuracy for financial data

---

## 🤖 Models Implemented
- GRU (Gated Recurrent Unit)
- LSTM (Long Short-Term Memory)
- CNN-LSTM (Hybrid Convolutional + Recurrent model)
- BiLSTM with Attention mechanism
- Transformer (Self-attention based model)

---

## 📊 Workflow
1. Data Collection (Crawling from Investing)
2. Data Preprocessing (cleaning, normalization)
3. Exploratory Data Analysis (EDA)
4. Feature Engineering (lag features, scaling)
5. Model Training & Hyperparameter Tuning
6. Multi-horizon Forecasting (30 / 60 / 90 days)
7. Evaluation & Model Comparison

---

## 📈 Evaluation Metrics
- RMSE (Root Mean Squared Error)  
- MAE (Mean Absolute Error)  
- MAPE (%) – relative prediction error  
- DPA (%) – Directional Prediction Accuracy (correctly predicted price movement direction)

---

## 🛠️ Tech Stack
- Python (Pandas, NumPy)
- TensorFlow / PyTorch
- Scikit-learn
- Matplotlib / Seaborn

---

## 🚀 Key Highlights
- Comparative study of multiple deep learning models
- Multi-horizon forecasting (30, 60, 90 days ahead)
- Application of attention mechanisms in financial forecasting
- Exploration of Transformer architecture for time series
- Evaluation using both error-based and direction-based metrics (DPA)

---

## 🔮 Future Work
- Incorporate macroeconomic indicators (oil prices, CPI, interest rates)
- Hyperparameter optimization (Optuna, Grid Search)
- Real-time forecasting pipeline
- Deploy forecasting system as a web application (Streamlit / Flask)
