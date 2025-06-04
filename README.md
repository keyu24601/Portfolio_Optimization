# Portfolio Optimization in Continuous Time
This project focuses on portfolio optimization in continuous time, analyzing the optimal investment strategies based on Merton’s portfolio theory and Markowitz mean-variance framework. 

## Project Overview
The analysis covers two main parts:
Part 1: Analyze profitability of Merton’s optimal portfolio for all Dow Jones stocks based on the perceived drifts for each individual stock.
Part 2: Analyze profitability of currency triplets based on the perceived mean reversion in the market for each triplet in the G10 currencies.

## Project Details
### Part 1: Stock Portfolio Optimization

- **Data Acquisition:** Collect historical price data for DJIA stocks starting from January 1, 2010. Calculate simple returns and volatilities for each stock.
- **Merton’s Optimal Portfolio:** Use the drift parameter (µ) under the physical measure to compute the optimal portfolio weights based on the geometric Brownian motion model.
- **Markowitz Portfolio:** Construct mean-variance portfolios by calculating optimal weights for each asset.
- **Performance Comparison:** Plot price evolutions of Merton’s, Markowitz’s, and fully risky portfolios; compute performance metrics such as Sharpe ratio and maximum drawdown.
- **Hedging Strategy:** Verify the hedging effectiveness of Merton’s portfolios and visualize the results.
- **Bayesian Merton Portfolio:** Extend the model by assuming drift parameter µ follows a normal distribution; compare the performance against the standard Merton portfolio.

### Part 2: Currency Triplets Portfolio Analysis
- **Mean-Reverting Market Assumption:** Model simple returns using subjective and objective covariance matrices to reflect mean reversion.
- **Optimal Portfolio Calculation:** Determine optimal portfolio weights for 36 EUR-based G10 currency triplets.
- **Performance Evaluation:** Graph portfolio values and calculate performance statistics.
- **Hedging Positions:** Compute and compare hedging positions with theoretical prices, illustrating these in visual graphs.
