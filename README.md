# Stock-Timer-Series
Initial Upload: 3/31/2025

Data 580D -- Analytics for Enterprise Apps

Project Objective: Write a python script to scrape stock price historical data for time series analysis

Project Tools: Utilizes a basic python script, initially coded through Jupyter Notebook. Additionally, the following libraries are required:
* pandas
* yfinance
* datetime
* matplotlib.pyplot
* statsmodels
* sklearn
* tensorflow*


Note: Tensorflow version 2.16.2 was utilized as other versions assumed VTX capabilities. If you encounter issues with tensorflow, attempt to deprecate version used to 2.16.2. 

# Motivation
Scraping finance data from the Web offers valuable insights that come in handy in various scenarios, including:
* A time series is a sequence of data points recorded at successive time intervals, used to analyze trends, patterns, and forecasts over time.
* Historical vs. Predicted Data – Stock prices can be analyzed by comparing past trends with future predictions to identify patterns.
* Decomposition into Four Components – Both historical and predicted stock data can be broken into Trend, Seasonality, Cyclical, and Residual components.
* Understanding Market Movements – Trend shows long-term growth, seasonality highlights recurring patterns, and cyclicality captures economic fluctuations.
* Residual Analysis – The residual component represents unpredictable variations, helping assess the accuracy of stock price predictions. • Capturing Temporal Dependencies: LSTMs excel in processing time-series data by remembering past patterns, making them ideal for stock price prediction.

## Dictionary
Five files are included within this repository. 
### Download_Historical_Data.ipynb
* Scrapes the historical stock data of a given company from a given year to the modern day, exporting as a csv file.
### Time_Series_Model.ipynb
* Creates a time series graph of a given company from a given year to the modern day, as well as trains a LSTM model on this data.
### TimeSeries_HistoricalAnalysis.ipynb
* Decomposes the time series model into four graphs: trend, seasonality, cyclicality, and residual.
### TimeSeries_Prediction.ipynb
* Predicts the stock prices for a given company over a period of time.
### TimeSeries_PredictionAnalysis.ipynb
* Decomposes the predictive model into four graphs: trend, seasonality, cyclicality, and residual.

## Usage


# Attributions
Template for README.md derived from David Freitag (https://github.com/dkfreitag/chicago_crime_project)

Additional assistance provided by Dr. Sumantra Sarkar and GA Purna Jadhav
