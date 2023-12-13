# Cryptocurrency Price Anomaly Detection


## Overview

This project focuses on detecting anomalies in cryptocurrency price data, specifically for the BTC/USDT trading pair. It utilizes the Binance API to retrieve historical price data, processes the data using Python and Pandas, and employs statistical analysis to identify anomalies.

## Features

- Fetches historical cryptocurrency price data using the Binance API.
- Utilizes Pandas for data manipulation and analysis.
- Implements anomaly detection based on percentage change in closing prices.
- Visualizes detected anomalies on a time-series plot.

## Installation

1. Clone the repository:

   git clone https://github.com/marzookcyril/Anomaly.git
   cd Anomaly

2.  Install the required dependencies:

    pip install -r requirements.txt


3. Obtain API Key and Secret from Binance:

    https://www.binance.com/en/support/faq/360002502072Update 

4. Update config.py with your Binance API Key and Secret:
    API_KEY = 'your-api-key'
    API_SECRET = 'your-api-secret'

