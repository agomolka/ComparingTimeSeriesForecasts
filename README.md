# Prophet Forecast Comparison 📊⚡

This project showcases a comparison of time series forecasting models and visualizes the results using an interactive dashboard built with Dash and Plotly. The models compared in this project include both traditional statistical methods and modern machine learning techniques:

- Prophet 📅🔮
- ARIMA 📈🔍
- XGBoost 🚀🌳
- LSTM 🧠🔍

### Comparison Approach

The primary goal of this project is to compare the forecasting performance of Prophet against more traditional approaches like ARIMA, machine learning models like XGBoost and LSTM. We aim to validate whether Prophet's capabilities justify its integration into forecasting pipelines or if sticking with well-established methods is more advantageous.

#### Methodology

1. **Data Preparation**: Pre-process the AEP Hourly dataset, handling missing values and scaling if necessary.
   
2. **Model Training and Evaluation**:
   - Train each model (Prophet, ARIMA, XGBoost, LSTM) on a subset of the data.
   - Evaluate each model's performance using metrics such as Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).
   
3. **Comparison and Interpretation**:
   - Visualize and interpret the forecasting results using an interactive dashboard.
   - Compare forecast accuracy and computational efficiency across models.
   
By comparing these approaches comprehensively, we aim to provide insights into which method suits the forecasting needs of the AEP Hourly dataset best, balancing accuracy, interpretability, and computational complexity.

## Data Source 📈🔌

The dataset used is the AEP Hourly dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption). The dataset provides hourly electricity consumption data from PJM Interconnection LLC (PJM), a regional transmission organization (RTO) in the United States. PJM operates an electric transmission system serving parts of several states and regions across the Eastern Interconnection grid.

### Hourly Energy Consumption Data 🌍⚡

PJM's hourly power consumption data is recorded in megawatts (MW). Due to changes in regional boundaries over time, data availability may vary for different dates and regions.

## Installation 🛠️

To run this project locally, ensure you have Python installed, along with the following libraries:

- pandas 🐼
- numpy 🧮
- plotly 📊
- dash 🎛️
- fbprophet 🔮
- statsmodels 🔍
- scikit-learn 🧬
- tensorflow 🧠
