# Crypto Price Predictor
Crypto Price Predictor is a Python project that predicts whether the price of Bitcoin will go up or down the next day using historical market data. It demonstrates data fetching, preprocessing, feature engineering, and predictive modeling with Logistic Regression. The notebook includes visualizations and statistics for better understanding and interpretability of predictions.

---

## Features
- Fetches historical Bitcoin prices from the **CoinGecko API** (last 180 days by default)  
- Calculates technical indicators used for prediction:  
  - Daily return  
  - 5-day moving average
  - 10-day moving average  
  - 5-day price volatility  
- Creates labels for next-day price movement (up/down)  
- Trains a **Logistic Regression model**  
- Evaluates performance with:  
  - Accuracy  
  - Confusion matrix  
  - Classification report  
- Visualizes:  
  - Historical prices with predicted movements  
  - Model performance metrics  
- Prints simple statistics:  
  - Number of days analyzed  
  - Days price went up/down  
  - Average daily return and volatility  

---

## Technologies Used
- Python 3.14  
- pandas, numpy  
- scikit-learn (Logistic Regression, StandardScaler)  
- matplotlib / seaborn (optional, for visualization)  
- requests (API data fetching)  
