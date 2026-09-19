# Data Science Capstone Project
## Daily Demand Forecasting Using ARIMA Time-Series Modeling

### Project Overview

This project focuses on forecasting daily demand using time-series analysis and the ARIMA (AutoRegressive Integrated Moving Average) model.

The project analyzes historical demand patterns, performs time-series decomposition, tests stationarity using the Augmented Dickey-Fuller (ADF) test, develops an ARIMA model, and evaluates its forecasting performance.

### Research Question

How effectively can an ARIMA model forecast future daily demand based on historical demand patterns?

### Objectives

- Analyze historical daily demand data.
- Identify trend, seasonal, and residual components.
- Test the stationarity of the demand series.
- Develop an ARIMA forecasting model.
- Evaluate model performance using RMSE and MAPE.
- Generate a 7-day future demand forecast.
- Discuss practical applications and limitations.

### Dataset

The dataset contains daily demand observations along with information about marketing events and holidays.

Main variables:

| Variable | Description |
|---|---|
| date | Date of the demand observation |
| demand | Daily demand value |
| marketing_event | Indicates whether a marketing event occurred |
| holiday | Indicates whether the day was a holiday |

### Methodology

The project follows these major steps:

1. Data loading and preprocessing
2. Exploratory Data Analysis
3. Time-series visualization
4. Time-series decomposition
5. Augmented Dickey-Fuller (ADF) stationarity test
6. Train-test split
7. ARIMA(1,1,1) modeling
8. Forecasting
9. Model evaluation
10. 7-day future demand forecasting

### Model Evaluation

The ARIMA(1,1,1) model achieved the following results on the testing dataset:

| Metric | Result |
|---|---:|
| RMSE | 14.62 |
| MAPE | 6.39% |

The model was also used to generate a 7-day future demand forecast.

### Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Jupyter Notebook / Google Colab

### Repository Contents

- `Data_Science_Capstone_Demand_Forecasting.ipynb` – Complete analysis and implementation
- `Data_Science_Research_Report_Daily_Demand_ARIMA.pdf` – Research report / whitepaper
- `daily-demand-series.csv` – Dataset used for analysis
- `README.md` – Project documentation

### Conclusion

This project demonstrates the application of ARIMA-based time-series forecasting to historical daily demand data. The developed model was evaluated using RMSE and MAPE and was used to produce short-term future demand forecasts.

### Future Work

Future improvements could include:

- Using a larger historical dataset
- Incorporating holidays and marketing events as external predictors
- Comparing ARIMA with SARIMA, Prophet, and machine-learning models
- Performing systematic hyperparameter selection
- Exploring ensemble forecasting approaches
