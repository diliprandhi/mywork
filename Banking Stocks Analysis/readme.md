# Banking Stocks Analysis

## Summary:
The Banking Stocks Analysis project is a detailed financial analysis of major Indian banks' stock performance. By extracting stock data from Yahoo Finance, the project aims to understand stock price trends, trading volumes, and other significant financial metrics over time. This analysis provides insights into the financial health and performance of these banks.

## Detailed Description:
The project begins with data extraction using the yfinance library. This library is used to download historical stock data for major Indian banks. The data includes daily stock prices, trading volumes, and other relevant metrics.

**Key analytical steps include:**

- **Time Series Analysis:** Plotting stock prices and trading volumes over time to identify trends. Line charts are used to visualize how stock prices and volumes fluctuate over the analysis period.
- **Moving Averages:** Calculating short-term (20-day), medium-term (50-day), and long-term (100-day) moving averages. These averages help smooth out price data to better identify underlying trends and potential buy/sell signals.
- **Daily Returns Analysis:** Computing the daily percentage change in stock prices. This analysis helps understand the volatility of each bank’s stock and is visualized using pie charts to categorize the returns into different segments.
- **Correlation Analysis:** Evaluating the correlation between the daily returns of different bank stocks. This is crucial for investors looking to diversify their portfolios. The results are visualized using heatmaps to highlight the strength of the correlations.
The project makes extensive use of visualization tools to present findings clearly and effectively. Visualizations include line plots, pie charts, and heatmaps, all designed to make complex financial data more accessible.

### Technologies Used:
- Python (Pandas, NumPy)
- yfinance for data extraction
- Matplotlib and Seaborn for data visualization

### Usage:
Clone the repository, install the necessary libraries, and run the script to generate visualizations and analyze the stock performance of major Indian banks.
