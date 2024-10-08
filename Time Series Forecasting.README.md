# Time Series Forecasting with Excel

## Overview
This project involves time series analysis and forecasting of sales data from a coffee shop using Microsoft Excel. The primary goal is to predict future sales based on historical data through exponential smoothing methods and trend analysis.

## Dataset
The dataset used for this analysis consists of transactional data, including:
- **Date**: The date of the transaction.
- **Sales**: Total sales for the day.

The dataset is available in the **coffee_shop_daily_sales.xlsx** file.

## Tools and Techniques
- **Microsoft Excel**: Used for data analysis and forecasting.
- **Functions Used**:
  - `FORECAST.ETS`: To perform exponential smoothing and forecast future values.
  - `FORECAST.ETS.SEASONALITY`: To determine the seasonal cycle length in the sales data.
  - **Trend Line**: Used to visualize and analyze the trend in sales data over time.

## Steps to Analyze and Forecast Sales
1. **Data Preparation**:
   - Cleaned the dataset to ensure it contains no missing values and is properly formatted.
   - Aggregated daily sales data for analysis.

2. **Analyzing Seasonality**:
   - Used the `FORECAST.ETS.SEASONALITY` function to identify the seasonal pattern in the sales data, which returned a seasonality value of **31**, indicating a monthly seasonal cycle.

3. **Exponential Smoothing and Forecasting**:
   - Applied the `FORECAST.ETS` function to predict future sales for specified dates.
   - Used the results of the seasonal analysis to understand recurring sales patterns.
    ![Screenshot (213)](https://github.com/user-attachments/assets/6308d73d-c5c9-41be-be25-8151ac85265a)

4. **Trend Line Analysis**:
   - Added a trend line to the sales data chart to visualize the overall direction of sales over time.
   - Analyzed the trend line to identify whether sales are generally increasing, decreasing, or remaining stable.
     ![Screenshot (216)](https://github.com/user-attachments/assets/4511ea49-2fe6-4782-8aeb-cf951d12ce5f)

5. **Exponential Smoothing**
   -Done using Data analysis toolpak.
    ![Screenshot (217)](https://github.com/user-attachments/assets/d0f91107-df03-4144-b85e-f4532f41c45d)

## Example Formulas
### Seasonality Calculation
To determine the seasonal pattern:
```excel
=FORECAST.ETS.SEASONALITY(B2:B32, A2:A32)
