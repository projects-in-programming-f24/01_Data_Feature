# PPDS - Activity 01 - Data Features

This Jupyter notebook demonstrates the creation of a simple data feature prototype that helps users find news articles related to a specific stock ticker.

## Features

- Converts a stock ticker symbol to a company name using the Alpha Vantage API
- Searches for related news articles using the New York Times Article Search API
- Displays up to 10 recent articles about the specified company

## Prerequisites

To run this notebook, you need to set up API keys for:

1. Alpha Vantage API (for stock ticker to company name conversion)
2. New York Times API (for article search)

Make sure to add these API keys to the `SECRETS` tab in Google Colab.

## Usage

1. Run the notebook cells in order.
2. When prompted, enter a stock ticker symbol (e.g., AAPL for Apple Inc.).
3. The notebook will display up to 10 recent news articles related to the company.

## Note

This is a prototype for educational purposes. In a real-world application, additional features such as a user interface, ability to add/remove tickers, financial metrics, and robust error handling would be implemented.
