# Stock Price Prediction Web Application

## 📚 Overview

This project is a Flask-based web application for stock price prediction using a deep learning model (`LSTM`). The app integrates with **Yahoo Finance** to fetch historical stock data, trains an LSTM model (built and trained in a Colab notebook and saved as `stock_dl_model.h5`), and visualizes predicted prices along with Exponential Moving Averages (EMA). The web interface is built using Flask.

---

## 🚀 Features

- Predict stock prices based on historical data.
- Interactive visualizations of stock trends and EMA charts (20 & 50 day, 100 & 200 day).
- Downloadable dataset in CSV format.
- User-friendly web interface powered by **Flask**.
- Displays descriptive statistics of the downloaded stock data.

---

## 🧑‍💻 Tech Stack

- **Backend:** Flask
- **Deep Learning Model:** TensorFlow (LSTM)
- **Data Visualization:** Matplotlib
- **Data Fetching:** yfinance
- **Data Scaling:** Scikit-learn
- **Numerical Computation:** NumPy
- **Data Manipulation:** Pandas

---

## 📦 Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/Stock-Price-Prediction-WebApp.git
   cd Stock-Price-Prediction-WebApp
