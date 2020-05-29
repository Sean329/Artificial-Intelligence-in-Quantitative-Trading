# Quant Trading Strategies

Build strategies for algo trading

### Project 1 - Trading with Momentum

For each month-end observation period, rank the stocks by previous returns, from the highest to the lowest. Select the top performing stocks for the long portfolio, and the bottom performing stocks for the short portfolio.

### Project 2 - Breakout Strategy

Create long/short signals when a breaking out of the previous consolidation area happens.

### Project 3 - Smart Beta Portfolio and Portfolio Optimization

Smart beta has a broad meaning, but we can say in practice that when we use the universe of stocks from an index, and then apply some weighting scheme other than market cap weighting, it can be considered a type of smart beta fund. A Smart Beta portfolio generally gives investors exposure or "beta" to one or more types of market characteristics (or factors) that are believed to predict prices while giving investors a diversified broad exposure to a particular market. Smart Beta portfolios generally target momentum, earnings quality, low volatility, and dividends or some combination. So the objective of this project is to design a portfolio that closely tracks an index, while also minimizing the portfolio variance. If this portfolio can match the returns of the index with less volatility, then it has a higher risk-adjusted return (same return, lower volatility).

### Project 4 - Alpha Research and Factor Modeling

In this project, I built a statistical risk model using PCA. I used this model to build a portfolio along with 5 alpha factors, then evaluated them using factor-weighted returns, quantile analysis, sharpe ratio, and turnover analysis. Finally, I optimized the portfolio using the risk model and factors using multiple optimization formulations.

The 5 Alpha factors and their hypotheses are:

1. Momentum 1 Year Factor: "Higher past 12-month (252 days) returns are proportional to future return."

2. Mean Reversion 5 Day Sector Neutral Factor: "Short-term outperformers(underperformers) compared to their sector will revert."

3. Overnight Sentiment Factor: inspired by this research paper https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2554010

4. Mean Reversion 5 Day Sector Neutral Smoothed Factor: It's a smoothed version of Factor 2

5. Overnight Sentiment Smoothed Factor: It's a smoothed version of Factor 3
