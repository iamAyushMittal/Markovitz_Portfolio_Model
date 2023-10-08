# Markovitz_Portfolio_Model
Creating an optimized portfolio 

While investing in such funds is a popular choice, I believe that there's a unique charm in crafting your stock portfolio and optimizing it to align with your risk tolerance and desired returns. However, it's essential to remember that in finance, we discuss about expected returns.

Understanding the two primary types of risk is crucial in this endeavor:

1. Systematic Risk: This pertains to macro-related risks like political factors.
2. Unsystematic Risk: This is specific to individual companies.

When building a portfolio, our focus is on minimizing unsystematic risk through diversification. By investing in multiple stocks, we aim to reduce the impact of individual company-specific risks.

Here's my seven-step approach that I followed for crafting an optimized portfolio:

1. Choose the number of stocks to invest in (I selected my 15).
2. Downloaded the daily returns of these stocks for the past year.
3. Then calculated the average daily returns for each stock.
4. Computed the excess daily return matrix (average return minus daily return).
5. Calculated the Variance-Covariance Matrix using the excess return matrix.
6. Determined standard deviations and create a correlation matrix.
7. Calculate weighted standard deviations to arrive at daily portfolio variance/standard deviation.

Now, with portfolio variance, returns, and asset weights in hand, the final step is to optimize these weights based on specific conditions. My chosen conditions include fixing the portfolio's standard deviation at 20% and setting a minimum weight of 2.5% for each stock. By optimizing the weights while maximizing portfolio returns, the result was portfolio return 93.89%.

