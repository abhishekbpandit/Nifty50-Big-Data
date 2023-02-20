## Stock Price Prediction

This repository contains code for predicting stock prices using machine learning techniques. The goal of this project was to predict whether the close price of stocks in the NIFTY 100 index would be higher or lower than the day before. Additionally, the project also aimed to predict short-term stock prices using the ARIMA model.

## Data

The data used in this project was ***minute-by-minute stock prices for 100 stocks*** in the NIFTY 100 index. The data was summarized on a daily basis and 55 technical indicators, along with the sectors of the stocks, were used as features for prediction. For further details, refer https://www.kaggle.com/datasets/debashis74017/stock-market-data-nifty-50-stocks-1-min-data

## Approach

The approach for the prediction was to use machine learning models to learn from the technical indicators and sectors of the stocks to make predictions. The following models were used:

- Gradient Boosting Classifier (GBT)
- Gradient Boosting Classifier with PCA to reduce training time
- Random Forest with hyperparameter tuning
- ARIMA

## Technologies

The following technologies were used in this project:

PySpark
Google Cloud Platform (GCP)
Google Cloud Storage (GCS)
Google Dataproc
Findings

The findings of this project indicate that the ***GBT Classifier performed the best*** with an AUC of 0.79. The GBT with PCA was underwhelming while the Random Forest was almost as good as the GBT for this problem.

## Note

The code in this repository is for educational purposes only and should not be used for making financial decisions. The results of this project may not be representative of the actual stock market.
