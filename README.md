# Forecasting-Using-Time-Series-Models
Forecasting Daily Bike Rental Demand Using Time Series Models
Sure, here's a README file for the bike rental demand forecasting project:

# Bike Rental Demand Forecasting

## Project Overview
This project aims to forecast daily bike rental demand using time series analysis and modeling techniques. The analysis explores the bike rental data, identifies key patterns and relationships, preprocesses the time series data, and builds ARIMA models for forecasting future demand.

## Data
The dataset used in this project contains the daily count of rental bike transactions between 2011 and 2012 in the Capital Bikeshare system, along with corresponding weather and seasonal information. The data is sourced from the UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset

## Analysis
The analysis is divided into the following tasks:

1. **Data Exploration**: Load and explore the bike rental data, calculate correlations, and visualize relationships between variables.

2. **Time Series Plots**: Create interactive time series plots to visualize trends, seasonality, and anomalies in the data.

3. **Data Smoothing**: Smooth the time series data using techniques like exponential smoothing and moving averages.

4. **Stationarity and Decomposition**: Assess the stationarity of the time series data, decompose it into trend, seasonal, and residual components, and apply differencing if necessary.

5. **ARIMA Modeling and Forecasting**: Fit manual and automatic ARIMA models to the preprocessed data and use them to forecast future bike rental demand.

6. **Findings and Conclusions**: Summarize the key findings and conclusions from the analysis.

## Requirements
The analysis is performed in R, and the following packages are required:

- timetk
- lubridate
- forecast
- TTR
- tseries

## Usage
1. Clone the repository or download the project files.
2. Open the `R Project.Rmd` file in RStudio or your preferred R environment.
3. Install the required packages if not already installed.
4. Run the code chunks sequentially to reproduce the analysis.

## Results
The analysis provides insights into the relationships between temperature, seasonality, and bike rental demand. It also demonstrates the application of time series modeling techniques, such as ARIMA models, for forecasting future demand.

## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
