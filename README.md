# Sales_forecasting-
This project implements a Retail Sales Forecasting System using Linear Regression. It simulates two years of sales data with trend and seasonality, trains a model, and forecasts the next 90 days.

You can open and run this project directly in Google Colab using the link below:
1.Google Colab Notebook:
https://colab.research.google.com/drive/1OGgWMLi-r-pgjLswtSalD7OqimS42iUh?usp=sharing
2. Project Structure
Main Components:
generate_synthetic_data() – Creates daily synthetic sales data with trend & seasonality
feature_engineering() – Adds time-based features & dummy variables
train_and_forecast() – Trains model & predicts future sales
Main Block – Runs data generation, training, forecasting & visualization
3. Required Libraries
pandas, numpy, matplotlib, scikit-learn
4. Data GenerationSimulates realistic retail sales patterns using:
- Base Sales (random noise)
- Linear Trend
- Weekly Seasonality
- Yearly Seasonality (sine wave-based)
5. Feature Engineering
Adds:
Day of Week, Day of Month, Month, Year, Linear Trend.
Applies one■hot encoding for categorical features.
6. Model Training & Forecasting
Steps:
1. Prepare dataset
2. Train Linear Regression model
3. Create future dates
4. Generate forecasting features
5. Predict future sales
Outputs:
- Forecast series
- Historical dataset with features
7. Visualization
Plots show:
- Historical Sales
- Model In■Sample Fit
- Forecasted Sales- Forecast Start Marker
8. Forecast Summary
Displays:
- Forecasting range
- Total forecasted sales
- Average daily forecast
- First 5 forecasted days
- Last 5 forecasted days
9. How to Run
Run in terminal:
python sales_forecasting.py
Or open in Google Colab using the provided link.
10. Example Output
Generated 730 days of historical sales data.
Model trained using Linear Regression.
Forecasting 90 days...
11. Extensions
Possible improvements:
- ARIMA, Prophet, LSTM models
- Holiday features
- Multi■store forecasting
- Database integration
