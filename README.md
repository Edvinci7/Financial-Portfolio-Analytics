# Financial Portfolio Analytics Dashboard

## Project Overview

This project is an interactive Streamlit dashboard for portfolio performance and risk analysis.  
It uses Python to analyze historical equity price data, calculate portfolio returns, evaluate key risk metrics, and visualize portfolio behavior over time.

The goal of this project is to demonstrate how financial data can be transformed into portfolio-level insights that support investment analysis and monitoring.

## Key Features

- Analyze historical stock price data
- Convert prices into daily returns
- Construct an equal-weight investment portfolio
- Calculate key portfolio metrics:
  - Total Return
  - Annualized Return
  - Annualized Volatility
  - Maximum Drawdown
- Visualize portfolio performance using interactive charts
- Deploy the project as a Streamlit web application

## Tools Used

- Python
- pandas
- numpy
- Plotly
- Streamlit
- GitHub
- Streamlit Community Cloud

## Project Structure

```text
Financial-Portfolio-Analytics/
├── app.py
├── requirements.txt
├── README.md
└── utils/
    ├── __init__.py
    ├── data.py
    ├── metrics.py
    └── plots.py
