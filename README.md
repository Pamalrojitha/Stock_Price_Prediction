# 📈 Stock Price Prediction Using RNN, LSTM, and GRU

## 📌 Overview
This project applies **Vanilla RNN, LSTM, and GRU models** to predict **Google stock prices**, evaluating their ability to capture temporal dependencies in financial data. The study compares their effectiveness in **long-term memory retention, training speed, and accuracy**.

## ✅ Key Features
- ✅ **Implemented Vanilla RNN, LSTM, and GRU for time-series forecasting**  
- ✅ **Compared model performance using MAE & RMSE**  
- ✅ **Hyperparameter tuning (units, learning rate, dropout, batch size)**  
- ✅ **Early stopping applied to prevent overfitting**  
- ✅ **Predicted next-day stock price based on historical data**  

## 🛠 Tech Stack
- **Programming:** Python  
- **Frameworks:** TensorFlow, Keras  
- **Libraries:** NumPy, Pandas, Matplotlib, Scikit-learn  
- **Techniques:** Time-Series Forecasting, RNNs, LSTMs, GRUs  

## 📊 Results
| Model | MAE (Close Price) | RMSE (Close Price) |
|--------|------------------|------------------|
| Vanilla RNN | 0.010 | 0.012 |
| LSTM | 0.008 | 0.011 |
| GRU | 0.006 | 0.008 |
| Optimised Best model (LSTM) on test set| 0.031 | 0.038 |

## 🔮 Forecast
| Feature | Predicted Value |
|---------|----------------|
| **Next-Day Close Price** | **92.54** |

## 🚀 How to Run
```bash
git clone https://github.com/Pamalrojitha/Stock_Price_Prediction.git
cd Stock_Price_Prediction
pip install -r requirements.txt
jupyter notebook
