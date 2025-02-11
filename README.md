# 🏆 Kaggle Playground Series - Forecasting Sticker Sales  

This project aims to predict multiple years of sales for various Kaggle-branded stickers across different fictitious stores located in real-world countries. The dataset is fully synthetic but incorporates realistic effects such as seasonality, weekends, and holiday influences, making it a great playground for time-series forecasting.  

## 📂 Dataset  

The dataset for this competition is available on the Kaggle competition page: [Kaggle Playground Series - Season 5, Episode 1](https://www.kaggle.com/competitions/playground-series-s5e1/data).  

- **`train.csv`** – Contains historical sales data for each `date-country-store-item` combination.  
- **`test.csv`** – Requires predicting the number of items sold (`num_sold`) for each `date-country-store-item` combination.  
- **Evaluation Metric:** Mean Absolute Percentage Error (MAPE).  

## 🛠️ Approach  

The solution involves:  

1. **Exploratory Data Analysis (EDA)** – Understanding trends, seasonality, and data distributions.  
2. **Traditional Machine Learning Models:**  
   - Baseline models (mean/median predictions)  
   - LightGBM  
   - XGBoost  
3. **Deep Learning Models:**  
   - Recurrent Neural Networks (RNN)  
   - Transformers  
   - Long Short-Term Memory (LSTM) networks  
   - CNN + Attention Mechanisms  
