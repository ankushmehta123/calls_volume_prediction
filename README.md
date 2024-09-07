Datasets
Call_Details.csv: Contains datetime and call volume data used for training and testing SARIMA and LSTM models. This dataset includes timestamps and corresponding call counts, providing the foundational data for time series forecasting.

weather_holidays_weekends.csv: Includes exogenous variables such as weather conditions, holidays, and weekends. This dataset is used in conjunction with SARIMAX to enhance the prediction accuracy by accounting for external factors that may influence call volumes.

Notebook
main.ipynb: The primary Jupyter notebook that contains the implementation of the forecasting models. It includes code for data preprocessing, model training, evaluation, and visualization of results.
Final Results
results.csv: Contains the actual and predicted call volumes on the test data. This file provides a comparison between the observed values and the model’s forecasts, allowing for evaluation of the model’s performance and accuracy.

![Screenshot 2024-09-07 214321](https://github.com/user-attachments/assets/7d24276a-2777-4654-9ba6-ee837fcf5826)
