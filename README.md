# StockMarketInsights
StockMarketInsights is a Python toolkit for analyzing and visualizing stock market data. It fetches historical data from Yahoo Finance, calculates performance metrics like returns, mean, and standard deviation, and provides visualizations for stock trends and portfolio analysis, helping with data-driven investment decisions.

This Jupyter Notebook provides tools for analyzing stock market data using Python. The project leverages libraries like `pandas`, `numpy`, and `yfinance` to fetch, process, and analyze stock price trends and returns.

---

## Key Features

1. **Download Stock Data:**  
   Fetch historical data using Yahoo Finance.

2. **Load CSV to DataFrame:**  
   The function `convert_to_df` loads stock data from a CSV file into a Pandas DataFrame, ensuring data persistence between sessions.

3. **Daily Return Calculation:**  
   Compute the daily percentage returns for the stock.

4. **Return Analysis Over Time:**  
   Evaluate cumulative returns for a specific period.

5. **Visualization:**  
   Generate candlestick charts and other plots to visualize stock trends.

6. **Stock Price Visualization:**  
   Visualize a stock's adjusted closing price over a specified date range with the `price_plot` function.  
   - Includes grid lines and a light purple background for better clarity.

7. **Download Multiple Stocks:**  
   Fetch historical data of multiple stocks.

8. **Merging Stock Data:**  
   Consolidate data from multiple stocks into a single DataFrame, filtering by specific columns (e.g., 'Adj Close') for comparative analysis.

9. **Stock Performance Visualization:**  
   Use the `plot_return_mult_stocks` function to visualize the growth of an initial investment across multiple stocks.

10. **Stock Performance Metrics for Single Stock:**  
    - Calculate mean, standard deviation, and the coefficient of variation (risk relative to return) for a stock.

11. **Stock Performance Metrics for Multiple Stocks:**  
    - Display statistical insights for multiple stocks, including mean, standard deviation, and coefficient of variation.

12. **Comprehensive Stock Data Analysis:**  
    Demonstrate how all the functions can be used together for a complete stock analysis.

---

## Dependencies

To run this project, you need the following libraries:

- `pandas`
- `numpy`
- `yfinance`
- `matplotlib`
- `mplfinance`


