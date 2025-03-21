

⸻

Amazon Stock Price Analysis and Prediction

Overview

This project performs a comprehensive analysis of Amazon’s stock price data from 2000 to 2025, followed by the development of time series models for price prediction. The analysis includes exploratory data analysis (EDA), advanced feature engineering, and implementation of various traditional time series forecasting models.

Background

Amazon.com, Inc. is one of the world’s most valuable companies, revolutionizing online retail and cloud services through its Amazon Web Services (AWS) division. As of March 2025, Amazon has a market cap of $2.249 Trillion USD, making it the 4th most valuable company globally. This project aims to analyze historical stock performance and evaluate the effectiveness of different time series models in predicting future price movements.

Dataset

The dataset spans from 2000 to 2025 and includes daily stock price data with the following columns:
	•	date: Trading date
	•	open: Price at market open
	•	high: Highest price for that day
	•	low: Lowest price for that day
	•	close: Price at market close
	•	adj_close: Closing price adjusted for splits and dividend distributions
	•	volume: Number of shares traded

⸻

Project Structure

This project is organized into three main components:

1. Exploratory Data Analysis (EDA)
	•	Historical price and volume trends
	•	Daily returns distribution
	•	Yearly and monthly price patterns
	•	Correlation analysis
	•	Volatility assessment
	•	Seasonal decomposition
	•	Autocorrelation analysis

2. Feature Engineering
	•	Technical indicators (Moving Averages, RSI, MACD, Bollinger Bands)
	•	Volatility measures (ATR, rolling standard deviation)
	•	Price momentum features
	•	Date-based features
	•	Normalized price features
	•	Lag features

3. Time Series Modeling

Multiple traditional time series models are implemented and evaluated:
	•	Naive model (random walk)
	•	Seasonal naive model
	•	Simple Exponential Smoothing
	•	Holt-Winters Triple Exponential Smoothing
	•	ARIMA with optimized parameters
	•	SARIMA with weekly seasonality
	•	ARIMAX with exogenous variables

⸻

Key Findings

Stock Price Characteristics
	•	Amazon’s stock has shown significant growth and volatility over the analyzed period.
	•	Price movements exhibit non-stationary behavior, requiring differencing for time series modeling.
	•	Seasonal patterns exist but are less pronounced than in many other time series.
	•	Volume and price movements show moderate correlation during major market events.

Model Performance
	•	Traditional time series models face challenges with stock price prediction due to market complexity.
	•	Shorter forecast horizons (30 days) yield significantly better results than longer periods.
	•	Models incorporating seasonality and trend components generally outperform basic models.
	•	Exogenous variables improve prediction accuracy in ARIMAX models.
	•	Performance metrics show that _______ model provided the best overall results with a RMSE of _____ and R² of _____.

⸻

Technical Implementation

Prerequisites
	•	Python 3.8+

Required Libraries:

pip install pandas numpy matplotlib seaborn statsmodels pmdarima scikit-learn



⸻

How to Run
	1.	Clone the repository:

git clone https://github.com/yourusername/amazon-stock-analysis.git


	2.	Navigate to the project directory:

cd amazon-stock-analysis


	3.	Run the analysis script:

python analysis.py


	4.	View the results in the output directory.

⸻

Acknowledgments

Special thanks to Open Data Sources for providing the Amazon stock data.

⸻

