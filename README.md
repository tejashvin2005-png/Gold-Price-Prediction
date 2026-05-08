🪙 Gold Price Prediction using Data Mining
📌 Project Overview
This project focuses on predicting gold price trends using historical data and applying both classical time series models and deep learning approaches. The aim is to build a forecasting pipeline that helps understand market behavior and support financial decision‑making.

📊 Dataset
Source: Historical gold price dataset (10+ years)

Attributes:

Date (daily records)

Gold price (USD per ounce)

Target: Forecast future gold prices

🔍 Methodology
Data Preprocessing:

Converted date column to datetime format.

Sorted records chronologically.

Handled missing values and normalized price data.

Exploratory Data Analysis (EDA):

Visualized long‑term gold price trends.

Identified seasonal patterns and volatility.

Forecasting Models:

ARIMA (AutoRegressive Integrated Moving Average)

Prophet (Facebook’s time series forecasting library)

LSTM (Long Short‑Term Memory neural networks)

Evaluation Metrics:

RMSE (Root Mean Squared Error)

MAE (Mean Absolute Error)

Comparison of predicted vs actual trends

📈 Results
ARIMA provided a strong baseline for short‑term forecasting.

Prophet captured seasonality and trend shifts effectively.

LSTM achieved the lowest RMSE, showing better performance for long‑term predictions.

💡 Insights
Gold prices show clear long‑term upward trends with short‑term volatility.

Deep learning models like LSTM are more effective when large historical datasets are available.

Combining classical and modern approaches provides robust forecasting.

🎯 Applications
Financial Planning: Assists investors in anticipating gold price movements.

Risk Management: Helps hedge against market volatility.

Academic Use: Demonstrates time series forecasting techniques in data mining.

🚀 How to Run
Clone the repository.

Install dependencies:

bash
pip install -r requirements.txt
Run the notebook:

bash
jupyter notebook Gold_Price_Prediction.ipynb
