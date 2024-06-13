# Banking Stocks Analysis

## Description:
This project involves analyzing the stock prices of major Indian banking companies (Axis Bank, ICICI Bank, Kotak Bank, and HDFC Bank) to understand trends, trading volumes, moving averages, daily returns, and correlations.

### Technologies Used:
**Python Libraries:** yfinance, Pandas, NumPy, Matplotlib, Seaborn

### Project Breakdown:

**Data Extraction:**
- Use the yfinance library to download historical stock data for the selected banking companies.
- Extract data such as date, adjusted close price, and trading volume for each stock.

**Visualization:**
- Create line plots to visualize the change in stock prices over time for each company.
- Plot the trading volume over time to understand the liquidity and activity levels in the market.
- Compute and visualize moving averages (20-day, 50-day, and 100-day) to identify trends and smoothing effects in stock prices.
- Calculate and plot the daily return percentages to observe the daily gains or losses in stock prices.

**Trend Analysis:**
- Add a new column 'Trend' based on daily return percentages to categorize the stock performance (e.g., slight positive, negative, bull run, bear drop).
- Visualize the frequency of these trends using pie charts for each company to get a clear picture of the overall performance distribution.

**Correlation Analysis:**
- Create a consolidated DataFrame containing the adjusted close prices of all selected stocks.
- Calculate the correlation matrix to understand the relationships between the daily returns of different stocks.
- Visualize the correlation matrix using heatmaps to identify any strong or weak correlations among the stocks.

### Usage:
Clone the repository, install the necessary libraries, and run the script to generate visualizations and analyze the stock performance.
