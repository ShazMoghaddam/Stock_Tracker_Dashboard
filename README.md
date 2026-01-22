📈 Stock Tracker Dashboard

Stock Tracker Dashboard is a beginner-friendly Python project that fetches historical price data for major stocks using the Yahoo Finance API. The project demonstrates essential data science skills including data acquisition, cleaning, exploration, visualization, and basic trading strategy implementation.

All code runs in a Jupyter Notebook with clear markdown explanations, making it easy to follow and extend.

✅ Features

Fetch historical stock data using the yfinance library

Data cleaning and exploration with pandas

Visualizations using matplotlib

Simple Moving Average (SMA) crossover strategy to highlight buy/sell signals

Beginner-friendly and well-documented in a Jupyter Notebook

📌 Key Skills Demonstrated

Python programming

Data acquisition & cleaning

Exploratory data analysis

Data visualization

Basic trading strategy logic

Working with Jupyter Notebook

🛠️ Technologies Used
Technology	Purpose
Python	Main programming language
yfinance	Fetch stock price data
pandas	Data cleaning & manipulation
matplotlib	Data visualization
Jupyter Notebook	Interactive development
🚀 Getting Started
1. Clone the repository
git clone https://github.com/ShazMoghaddam/Stock_Tracker_Dashboard.git

2. Install required libraries
pip install yfinance pandas matplotlib notebook

3. Run the Notebook
jupyter notebook


Open the notebook file and run each cell in order.

🧠 Project Overview

This notebook walks through:

Selecting a list of major stocks (e.g. AAPL, AMZN, GOOGL, JPM)

Downloading historical data using Yahoo Finance API

Cleaning and exploring the data using pandas

Visualizing stock trends with matplotlib

Implementing SMA crossover strategy

Buy signal when short-term SMA crosses above long-term SMA

Sell signal when short-term SMA crosses below long-term SMA

📈 Moving Average Crossover Strategy

A simple strategy to identify trend changes:

Short-term SMA (e.g. 20-day)

Long-term SMA (e.g. 50-day)

Signals:

Buy: Short-term SMA crosses above long-term SMA

Sell: Short-term SMA crosses below long-term SMA

🧩 How to Extend the Project

You can improve this project by:

Adding more stocks or ETFs

Including additional technical indicators (e.g., RSI, MACD)

Implementing backtesting logic

Building a web dashboard using Streamlit or Dash

Adding real-time price tracking

📎 License

This project is open source and available under the MIT License.

📌 Contact

If you have any questions or feedback, feel free to contact me.
