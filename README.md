###  Report: Stock Market Performance Analysis


#### 1. Introduction

This report details the performance analysis of four leading technology companies: Apple Inc. (AAPL), Microsoft Corporation (MSFT), Netflix Inc. (NFLX), and Alphabet Inc. (GOOGL). The analysis covers a period of three months and encompasses trend analysis, moving averages, volatility measures, and correlation assessments.

#### 2. Data Collection

Historical stock price data was sourced using the `yfinance` API. The dataset includes daily records of:
- Open:  Opening price of the stock.
- High: Highest price during the trading day.
- Low: Lowest price during the trading day.
- Close: Closing price of the stock.
- Adjusted Close: Closing price adjusted for dividends and stock splits.
- Volume: Number of shares traded.

#### 3. Data Preprocessing

Data preprocessing steps included:
- Missing Values: No missing values were detected in the dataset.
- Daily Returns Calculation: The percentage change in the closing price from one day to the next was computed to determine daily returns.

#### 4. Trend Analysis

Trend Analysis: involves plotting the closing prices of each stock over the past three months to visualize their movements and identify trends.

- Apple Inc. (AAPL): Demonstrated a generally upward trend with several fluctuations. The stock showed resilience and growth potential.
- Microsoft Corporation (MSFT): Exhibited a steady upward trajectory, reflecting strong performance and stability in the market.
- Netflix Inc. (NFLX): Displayed significant volatility with frequent sharp movements, indicating a more unstable performance compared to its peers.
- Alphabet Inc. (GOOGL): Showed a relatively stable trend with moderate upward movements, suggesting consistent but less aggressive growth.

#### 5. Moving Averages

Moving Averages were computed to smooth price data and reveal longer-term trends. The following moving averages were used:
- 20-Day Moving Average: Represents short-term trends and captures recent price movements.
- 50-Day Moving Average: Represents long-term trends and provides insight into the overall direction.

- Apple Inc. (AAPL)    : The 20-day moving average frequently crossed the 50-day moving average, signaling periods of trend reversals and buying/selling opportunities.
- Microsoft Corporation (MSFT) : Showed a consistent positive slope in both moving averages, indicating a robust long-term upward trend with fewer fluctuations.
- Netflix Inc. (NFLX)  : Exhibited frequent crossovers between short-term and long-term moving averages, reflecting high volatility and potential trading opportunities.
- Alphabet Inc. (GOOGL): Demonstrated a steady trend with fewer crossovers, indicating a stable growth pattern.

#### 6. Volatility Analysis

Volatility     was measured by calculating the standard deviation of daily returns, providing insights into the risk associated with each stock.

- Apple Inc. (AAPL)    : Had moderate volatility, suggesting a balanced risk profile with periodic fluctuations.
- Microsoft Corporation (MSFT) : Exhibited the lowest volatility among the stocks, indicating relative stability and lower risk.
- Netflix Inc. (NFLX)    : Showed the highest volatility, reflecting greater risk and potential for substantial price swings.
- Alphabet Inc. (GOOGL)  : Displayed moderate volatility, suggesting a balanced risk profile with less extreme movements compared to Netflix.

#### 7. Correlation Analysis

The **correlation matrix** was computed to assess the relationships between daily returns of the different stocks. The correlation matrix helps in understanding how stocks move relative to each other:

-  High Positive Correlations : AAPL and MSFT showed high positive correlations, indicating that their returns tend to move in the same direction.
-  Moderate Positive Correlations: AAPL and GOOGL, as well as MSFT and GOOGL, exhibited moderate positive correlations, suggesting some level of synchronized movement.
-  Lower Correlation : NFLX demonstrated a lower correlation with the other stocks, indicating more independent price movements.

#### 8. Insights and Recommendations

1. **Trend Insights**:
   - AAPL and MSFT showed strong upward trends, making them attractive for investors seeking growth.
   - NFLX exhibited high volatility, suitable for traders looking for short-term opportunities but with higher risk.
   - GOOGL provided consistent, moderate growth, appealing to those seeking stability.

2. # Moving Average Insights:
   - Regular crossovers in **AAPL** and **NFLX** suggest active trading opportunities.
   - **MSFT** and **GOOGL** showed more stable trends, reflecting solid long-term investment potential.

3. # Volatility Insights:
   - NFLX presents higher risk but potential for higher returns.
   - MSFT offers lower risk and stability, making it suitable for conservative investors.

4. **Correlation Insights**:
   - Stocks with high positive correlations can be grouped for diversified investments.
   - Lower correlation with **NFLX** indicates potential benefits from diversification strategies.

#### 9. Conclusion

This analysis provides valuable insights into the performance, risk, and relationships of AAPL, MSFT, NFLX, and GOOGL. Investors can use these findings to make informed decisions, balancing potential returns with associated risks.

