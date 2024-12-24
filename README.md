# Demand Forecasting Project

This project focuses on developing a demand forecasting model for e-commerce using advanced time series analysis and regression techniques. The model uses historical sales data, as well as key performance indicators (KPIs) from Google Analytics (clicks,impressions, quantity), to predict future product demand.

## Project Overview

The goal of this project is to predict future product demand using historical sales data, along with other relevant metrics. By leveraging various time series models and regression techniques, this system helps businesses forecast demand accurately and make data-driven decisions for inventory management, sales strategy, and marketing campaigns.

## Key Features

- **Time Series Models**: 
  - ARIMA (AutoRegressive Integrated Moving Average)
  - SARIMA (Seasonal ARIMA)
  - AR (AutoRegressive)
  - MA (Moving Average)
  - ARIMAX (ARIMA with exogenous variables)
  - SARIMAX (Seasonal ARIMAX)
- **Hyperparameter Tuning**: Optimizing model parameters for improved forecasting accuracy.
- **Multivariate Regression**: Combining multiple features (e.g., sales, clicks, and impressions) for better demand prediction.
- **Data Preprocessing**: Handles missing values, merges datasets, and prepares data for model training.
- **Visualization**: Visualizes trends, patterns, and model performance.
  
## Technologies Used

- **Python**
- **Pandas**: For data manipulation and preprocessing.
- **Matplotlib/Seaborn**: For data visualization.
- **Scikit-learn**: For regression modeling and hyperparameter tuning.
- **Statsmodels**: For time series modeling (ARIMA, SARIMA, etc.).
- **Jupyter Notebooks**: For interactive data analysis and model development.

## Data

The project uses three main datasets:

1. **Sales Data**: Historical data for product sales.
2. **Google Analytics**: Data for Google clicks and impressions.
3. **Facebook Impressions**: Data on Facebook impressions for product ads.

These datasets are merged to create a comprehensive dataset for forecasting.

## Data Preprocessing

The preprocessing steps involved:
- Merging multiple datasets into one master dataset.
- Handling missing values by imputing or dropping records.
- Feature engineering to create new columns (e.g., weekdays, weekends).
- Visualization of trends and correlations for model selection.

## Model Development
### Time Series Models:
- **ARIMA**: A basic univariate model that accounts for autocorrelation in the data.
- **SARIMA**: Extends ARIMA by adding seasonal components to better capture periodic patterns.
- **AR and MA**: Models focusing solely on autocorrelation (AR) or moving averages (MA).
- **ARIMAX and SARIMAX**: Incorporating external variables (e.g., Google clicks, Facebook impressions) into the ARIMA and SARIMA models to improve prediction accuracy.

### Hyperparameter Tuning:
- Used techniques such as grid search and cross-validation to fine-tune model parameters for optimal performance.

### Multivariate Regression:
- Implemented multivariate regression models to combine external factors and sales data for improved predictions.

