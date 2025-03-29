
# 📈 Sentiment-Analysis-based-Stock-Market-Recommendation-System-using-Two-Phase-Approach

This project develops a **hybrid stock market prediction system** by integrating **sentiment analysis and deep learning-based technical analysis** to forecast Apple Inc. (AAPL) stock trends.

## 🚀 Approach  

### 📌 Phase 1: Sentiment Analysis  
- Collected real-time **financial news** using the **Alpha Vantage API**.  
- Preprocessed text data and analyzed sentiment using **FinBERT**, a transformer-based model fine-tuned for financial sentiment classification.  
- Aggregated sentiment scores to predict **next-day stock movement**.  

### 📌 Phase 2: Technical Analysis  
- Gathered **10 years of stock price data (200,000+ records)** via the **Yahoo Finance API**.  
- Engineered **time-series features** and **scaled data** for forecasting.  
- Implemented multiple deep learning models:
  - **Combination of FB Prophet & Multivariate Attention-Based Stacked LSTM** 
  - **Multivariate Attention-Based Stacked LSTM**   
  - **Bidirectional LSTM**  
  - **Simple LSTM**  
- Achieved **high prediction accuracy**:  
  - **R² = 0.925**  
  - **RMSE = 3.93**  
  - **MAPE = 2.08%**  
- Outperformed baseline models in forecasting stock prices.  

## 🛠️ Technologies Used  
- **Python**  
- **TensorFlow**  
- **Yahoo Finance API**  
- **Alpha Vantage API**  
- **FinBERT**  
- **FB Prophet**  
- **LSTM Variants**  

📌 *This project was presented at the **3rd International Conference on Innovative Technologies, NIT Srinagar.***
