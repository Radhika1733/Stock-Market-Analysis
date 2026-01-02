# Stock Market Analysis of Apple, Microsoft, Cisco, and Meta

## Overview:
This project analyzes the stock price behavior of four major tech companies – Apple (AAPL), Microsoft (MSFT), Cisco (CSCO), and Meta (META), over three months. We retrieved daily stock data using the Yahoo Finance API (yfinance) and performed a series of analyses to understand each stock's performance, risk, and relationships.

## Data Collection:
We started by collecting historical data for each stock. Using the yfinance library, we downloaded daily price data for the past 3 months for Apple, Microsoft, Cisco, and Meta. This data includes each day’s Open, High, Low, Close, Adjusted Close, and Volume. All the data was then combined into a single dataset (with a ticker identifier) for analysis.

## Descriptive Statistics:
For an initial overview, we calculated descriptive statistics of the closing prices for each company. This summary included measures like the average closing price, the minimum and maximum price in the period, and the standard deviation of prices, which gives a quick snapshot of each stock’s typical price level and variability.

## Time Series Analysis:
We plotted the daily closing prices over time for all four stocks to visualize their trends across the three months. Visualizing the price trends makes it easy to identify which companies’ stocks were strengthening (upward trend) over the quarter and which were weakening (downward trend). 

## Volatility Analysis:
Next, we performed a volatility analysis to quantify how much each stock’s price fluctuated. We measured volatility as the standard deviation of the closing prices for each company over the period.

-> Understanding volatility is crucial for investors because it is essentially a measure of risk. A more volatile stock (like Meta in this analysis) can yield large gains in a short period but can also result in sharp losses – it’s less predictable. A less volatile stock (like Cisco) is more stable and less risky in the short term, which might suit risk-averse investors. Quantifying volatility gives a clear idea of which stock is riskiest to hold during that period and which is comparatively safer in terms of price stability.

## Correlation Analysis:
We then examined how the stock prices moved in relation to each other by computing a correlation matrix for the closing prices of Apple, Microsoft, Cisco, and Meta. 

-> Correlation analysis is useful for understanding diversification. If you hold highly correlated stocks, they will all tend to go up or down together, offering less risk reduction in a portfolio.

## Comparative Analysis (Percentage Change in Closing Prices)
We compared stock performance by calculating the percentage change in closing price over the three months. This metric indicates each stock's gains or losses, allowing for a clear performance comparison.

## Daily Risk vs. Return Analysis:
Finally, we calculated the daily returns for each stock (the percentage change in price each day), then took the average of these daily returns and the standard deviation of these returns for each stock. This analysis is crucial for evaluating risk-adjusted performance. It helps to answer whether a stock’s returns are commensurate with the risk taken.




