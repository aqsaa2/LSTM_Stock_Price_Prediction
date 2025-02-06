# Stock Price Prediction Web Application

## 📚 Overview

This project is a Flask-based web application for stock price prediction using a deep learning model (`LSTM`). The app integrates with **Yahoo Finance** to fetch historical stock data, trains an LSTM model (built and trained in a Colab notebook and saved as `stock_dl_model.h5`), and visualizes predicted prices along with Exponential Moving Averages (EMA). The web interface is built using Flask.

---

## 🎥 Video Demo

Check out the video demo of the Stock Price Prediction Web Application:

[![Video Demo](https://drive.google.com/file/d/186fhdroyS3iNLPtqvFcL5RDGkOes0iLP/view?usp=sharing)](https://drive.google.com/file/d/1N8IUqkI2K__fFkursc_7HF95IYVWcYxp/view?usp=sharing)

In this video, you will see how the app works, including:
- Fetching historical stock data.
- Visualizing stock price predictions with EMA trends.
- Downloading the dataset.
- Understanding the user interface.

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
   ```

2. Navigate to the project directory:


 ```bash
cd <project_directory>
 ```

3. Install the required dependencies:

 ```bash
pip install -r requirements.txt
 ```

## 🏃‍♂️ Running the Application

1. Run the Flask application:

```bash

python app.py
```

2. Open your browser and navigate to http://127.0.0.1:5000/ to access the web application.


## ⚙️ Usage

Enter the stock ticker symbol (e.g., OGDC.KA) in the input field and click "Predict".

The application will fetch historical data, generate predictions, and display:

Descriptive statistics of the stock data.
Visualizations of the stock's closing price with EMA trends.
Predicted vs. original stock price trends.
You can download the dataset as a CSV file by clicking the "Download Dataset" button.

## 🧰 Requirements

The requirements.txt file should contain the following Python packages (example):

 ```bash
Flask
pandas
numpy
scikit-learn
yfinance  # Or another data source library
matplotlib
 ```

