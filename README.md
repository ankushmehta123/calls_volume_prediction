<h1>Calls Volume Prediction</h1>

<h2>Datasets</h2>
<ul>
    <li><strong>Call_Details.csv</strong>: Contains datetime and call volume data used for training and testing SARIMA and LSTM models. This dataset includes timestamps and corresponding call counts, providing the foundational data for time series forecasting.</li>
    <li><strong>weather_holidays_weekends.csv</strong>: Includes exogenous variables such as weather conditions, holidays, and weekends. This dataset is used in conjunction with SARIMAX to enhance the prediction accuracy by accounting for external factors that may influence call volumes.</li>
</ul>

<h2>Notebook</h2>
<ul>
    <li><strong>main.ipynb</strong>: The primary Jupyter notebook that contains the implementation of the forecasting models. It includes code for data preprocessing, model training and evaluation.</li>
</ul>

<h2>Final Results</h2>
<ul>
    <li><strong>results.csv</strong>: Contains the actual and predicted call volumes on the test data. This file provides a comparison between the observed values and the model’s forecasts, allowing for evaluation of the model’s performance and accuracy.</li>
</ul>

<h2>Summary</h2>

![Screenshot 2024-09-07 214321](https://github.com/user-attachments/assets/7d24276a-2777-4654-9ba6-ee837fcf5826)
