# Stock Price Analysis Dashboard

## Overview
This project is a **Stock Price Analysis Dashboard** built using **Dash, Plotly, Keras, and Pandas**. It leverages **LSTM (Long Short-Term Memory) models** to predict stock prices and provides an interactive visualization of historical and predicted data.

## Features
- **Stock Price Visualization**: Displays actual and predicted closing prices for NSE-TATAGLOBAL stock.
- **LSTM Model for Prediction**: Uses a trained LSTM model to predict stock prices based on historical data.
- **Interactive Dashboards**: Provides different tabs for analyzing stock highs, lows, and trading volume.
- **Dropdown Selection**: Allows users to select stocks like Tesla, Apple, Facebook, and Microsoft for analysis.

## Technologies Used
- **Dash**: For building the interactive web application.
- **Dash Core Components (dcc)** & **Dash HTML Components (html)**: For UI elements.
- **Pandas**: For data preprocessing.
- **Plotly**: For data visualization.
- **Keras**: For loading and utilizing the LSTM model.
- **Scikit-learn (MinMaxScaler)**: For normalizing stock price data.

## Installation
### Prerequisites
Ensure you have **Python 3.7+** installed along with the following libraries:
```sh
pip install dash dash-core-components dash-html-components plotly pandas keras scikit-learn numpy
```

## Usage
### 1. Clone the Repository
```sh
git clone https://github.com/yourusername/stock-price-dashboard.git
cd stock-price-dashboard
```

### 2. Run the Dashboard
```sh
python app.py
```
The application will be available at `http://127.0.0.1:8050/` in your browser.

## File Structure
```
stock-price-dashboard/
│── saved_model.h5             # Pre-trained LSTM model
│── stock_data.csv             # Stock data for analysis
│── NSE-TATA.csv               # Tata Global historical stock data
│── app.py                     # Main Dash application script
│── README.md                  # Project documentation
```


## Future Enhancements
- Add more stock data sources (e.g., real-time API integration).
- Implement additional machine learning models.
- Enhance UI with more interactive visualizations.

---
_Developed with ❤️ using Python and Dash._

