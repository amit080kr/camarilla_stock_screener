# Stock Screener Using Camarilla Levels

This project is a **Stock Screener** designed to filter stocks in real-time during market hours using **Camarilla pivot levels**. 
It utilizes the [yfinance](https://github.com/ranaroussi/yfinance) library to fetch live stock market data and calculate Camarilla levels, providing a powerful tool to identify key trading opportunities.

---

## Features

- **Live Stock Data**: Fetch real-time market data using the `yfinance` library.
- **Camarilla Pivot Levels**: Automatically calculate Camarilla levels (`H1`, `H2`, `H3`, `H4`, `L1`, `L2`, `L3`, `L4`) for stocks.
- **Filtering Mechanism**: Screen stocks during market hours based on specific conditions (e.g., price breaking key levels like `H3` or `L3`).
- **Customizable Timeframes**: Fetch data in multiple intervals (`5m`, `1d`, etc.) for granular analysis.

---

## Project Overview

### Camarilla Pivot Levels
Camarilla levels are calculated using a stock’s **High**, **Low**, and **Close** prices from previous sessions. These levels act as key support and resistance zones and are widely used in intraday trading.

### Usage
This screener can:
1. Fetch historical and live data for multiple stocks.
2. Calculate Camarilla levels to the dataset.
3. Filter stocks meeting specific conditions (e.g., closing prices breaking `H3` or `L3` levels).

---
