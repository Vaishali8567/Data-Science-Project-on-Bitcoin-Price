# Data-Science-Project---Bitcoin-Price

**Assessing the Influence of Macroeconomic Indicators on Bitcoin Price Dynamics**

This project investigates how global macroeconomic indicatorsimpact Bitcoin price movements between 2017 and 2021. Machine learning models Support Vector Machine (SVM), Long Short-Term Memory (LSTM) networks and Extreme Gradient Boosting (XGBoost) are used to predict Bitcoin price trends.

**Data Source:** Kaggle (https://www.kaggle.com/datasets/sudalairajkumar/cryptocurrencypricehistory and https://www.kaggle.com/datasets/heidarmirhajisadati/global-economic-indicators-dataset-2010-2023)
Data Type: Tabular Data Time Frame: 2015–2023 Data Format: CSV
The Dataset contains: Time-series dataset containing cryptocurrency price trends. Date, Open Price, High Price, Low Price, Close Price, Volume. Inflation, GDP, interest rates, and unemployment. 

**Features Enginerred:** Bitcoin Return Rate, Volatility Index, Rolling Correlations

**Result Summary**
Model | RMSE | MAE | MAPE (%) | Directional Accuracy (%)
SVM | 17,375.73 | 10,292.28 | 42.09 | 52.56
LSTM | 6,549.84 | 2,912.14 | 9.05 | 53.59
XGBoost | 2,998.53 | 662.15 | 0.82 | 93.95
XGBoost outperformed SVM and LSTM with the lowest error rates and highest directional accuracy.

**How to Run the Code**

Libraries used: 
pandas, numpy, matplotlib, seaborn
sklearn, xgboost, shap
tensorflow, keras-tuner
scikit-optimize (for Bayesian Optimization)

Clone the repository: git clone https://github.com/Vaishali8567/Data-Science-Project-on-Bitcoin-Price.git
Install the required packages
Open and run the Jupyter Notebook
