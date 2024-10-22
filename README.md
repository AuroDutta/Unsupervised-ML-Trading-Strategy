# Unsupervised-ML-Trading-Strategy
This project aims to develop a trading strategy using unsupervised machine learning techniques to create and optimize a stock portfolio. By clustering stocks based on their features, we can form a diversified and optimized portfolio that aims to achieve the highest possible return for a given level of risk.

Overview
1. Download/Load SP500 Stocks Prices Data
First, we download or load historical price data for stocks in the S&P 500 index. This data serves as the foundation for all subsequent analysis.

2. Calculate Features and Indicators
For each stock, we calculate various financial indicators and features such as moving averages, volatility, momentum, and other technical indicators. These features help us understand the behavior of each stock to a certain extent.

3. Aggregate Data on a Monthly Level and Filter Top 150 Most Liquid Stocks
We aggregate the data to a monthly level to smooth out daily noise and focus on longer-term trends. We then filter out the top 150 most liquid stocks, which ensures we are working with stocks that have sufficient trading volume and liquidity.

4. Calculate Monthly Returns for Different Time Horizons
Next, we calculate the monthly returns for each stock over different time horizons. This helps us understand the performance of each stock over varying periods.

5. Download Fama-French Factors and Calculate Rolling Factor Betas
We download Fama-French factors, which are widely used in finance to explain stock returns. We calculate rolling factor betas for each stock, which measure how sensitive a stock's returns are to these factors over time.

6. Fit a K-Means Clustering Algorithm
For each month, we use a K-Means clustering algorithm to group stocks based on their calculated features and indicators. This allows us to identify clusters and groups of stocks that exhibit similar behavior.

7. Select Assets Based on Clusters and Form a Portfolio
Based on the clusters formed by the K-Means algorithm, we select assets to include in our portfolio. We then use Efficient Frontier optimization to form a portfolio that maximizes the Sharpe ratio, which measures risk-adjusted return.

8. Visualize Portfolio Returns and Compare to SP500 Returns
Finally, we visualize the returns of our optimized portfolio and compare them to the returns of the S&P 500 index. This comparison helps us evaluate the performance of our trading strategy.

By following these steps, the hope is to develop a robust trading strategy that leverages unsupervised machine learning techniques to optimize stock selection and portfolio construction.
