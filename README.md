# Cryptocurrency API Data Pull and Visualization Project

## Project Overview

This project aims to pull cryptocurrency data from the CoinMarketCap API, process the data, and visualize it using Seaborn and Matplotlib. The goal is to track the percentage change in cryptocurrency prices over various time intervals (e.g., 1 hour, 24 hours, 7 days) and generate insightful visualizations for analysis.

## Features

- Fetches cryptocurrency data from CoinMarketCap's API.
- Stores and updates cryptocurrency data over time.
- Normalizes and processes data into a structured format.
- Creates visualizations to display the percentage change in cryptocurrency prices.
- Supports plotting of multiple cryptocurrencies across different time intervals.

## Requirements

Before running the project, ensure that you have the following libraries installed:

- `requests`: For making API calls to the CoinMarketCap API.
- `pandas`: For handling data manipulation and storage.
- `seaborn`: For generating attractive statistical visualizations.
- `matplotlib`: For creating static plots.
- `json`: For parsing the API response.
- `time`: For controlling the timing of API pulls (with sleep).
- `os`: For handling file operations like reading/writing CSV files.

You can install the required packages using the following command:

```bash
pip install requests pandas seaborn matplotlib

