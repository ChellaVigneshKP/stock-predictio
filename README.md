Stock Price Prediction with LSTM Models
This repository contains a Flask web application for predicting stock prices using Long Short-Term Memory (LSTM) neural networks. The application fetches historical stock data from Yahoo Finance API (yfinance), preprocesses the data by adding moving average features, normalizes it using Min-Max scaling, and trains LSTM models with different hyperparameters.

Key Features
Data Preprocessing: Includes adding moving average features to enhance model performance.
Model Training: Utilizes LSTM models with varying architectures (layers, hidden dimensions, dropout) to predict stock prices.
Hyperparameter Tuning: Grid search over predefined parameters to optimize model performance.
Web Application: Built using Flask to allow users to input a stock ticker symbol and a date, then receive predictions for future stock prices.
Visualization: Generates plots using matplotlib to visualize predicted prices and backtesting results.
Backtesting Strategy: Evaluates a simple trading strategy based on predicted signals.
Technologies Used
Python
Flask
PyTorch (for LSTM models)
yfinance (Yahoo Finance API)
matplotlib (for plotting)
sklearn (for data preprocessing)
How to Use
Clone the repository:
bash
Copy code
git clone <repo_url>
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Start the Flask application:
bash
Copy code
python app.py
Navigate to http://localhost:5000 in your web browser.
Enter a stock ticker symbol and a recent date to get predictions and backtesting results.
Screenshots
Prediction Plot: Visualizes actual vs. predicted stock prices.
Backtesting Plot: Shows cumulative returns for the strategy and buy-and-hold approach.
Future Improvements
Incorporate more sophisticated feature engineering techniques.
Explore advanced LSTM architectures or other deep learning models.
Enhance the web interface with additional features and interactivity.
