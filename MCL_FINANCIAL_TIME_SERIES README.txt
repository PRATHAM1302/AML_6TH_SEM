Monte Carlo Simulation for Stock Prices - README


Introduction

This code uses Monte Carlo Simulation to forecast stock prices for a given company (in this case, American Airlines - AAL) based on its past stock prices.


Dependencies

NumPy: for performing mathematical operations

Pandas: for loading and handling the dataset

Matplotlib: for data visualization

SciPy: for statistical operations


Data

A CSV file named 'all_stocks_5yr.csv' is loaded using Pandas.
The data contains the opening, closing, highest and lowest stock prices for various companies for a period of 5 years.


Procedure

The data for a particular company (in this case, AAL) is filtered.

The logarithmic returns, mean, variance, drift/trend, and standard deviation of the logarithmic returns are calculated using statistical operations provided by SciPy.

A random noise is generated for a forecast of 250 time points (days) and 10 different forecasts using normal probability distribution and stored in a matrix called 'daily_returns'.

The last closing stock price of the company is obtained to start the simulation, which is stored in the variable 'S0'.

An empty matrix is created with the same shape as the 'daily_returns' matrix.

A for loop is used to perform Monte Carlo simulation, where each time the 'price_list' is updated by multiplying the previous price with the generated random noise.

The result of the Monte Carlo simulation is concatenated with the original closing stock prices to form a new dataset named 'monte_carlo_forecast'.

The first and last few rows of the 'monte_carlo_forecast' dataset are printed, and a line plot of the simulated stock prices is created using Matplotlib.


Conclusion

Monte Carlo Simulation is a powerful statistical tool for forecasting stock prices. By using this method, investors can have a rough estimate of how the stock prices might behave in the future based on historical data.