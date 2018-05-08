# Portfolio-Recommendation

Portfolio Recommendation Engine: To help naive investors make better decisions by suggesting an optimal portfolio based on user inputs which have an objective of minimizing risk given the approximate tolerance on the return.


## Backtesting

To run the code for backtesting (testing the historical performance of the portfolio), run the scripts backtest1.py (1-year backtest), backtest2.py (1-week backtest), and backtest3.py (6-month backtest). The scripts will plot the portfolio and SPY performance and print out portfolio and SPY statistics. The backtesting scripts utilize the codes:

optimization.py: Runs optimization and determines optimal portfolio
marketsim.py: Calculates value of optimal portfolio for backtesting period and plots it, and calculates portfolio statistics (cumulative return, average daily return, portfolio standard deviation, and sharpe ratio)

Requirements: Numpy, Pandas, Matplotlib, gurobipy

## UI

To run and demo the UI, simply run the app.py file, then go to the displayed URL. The app.py code utilizes the codes:

optimization.py: Runs optimization and determines optimal portfolio
portfoliosim.py: Calculates projections for portfolio value for the given time period

Requirements: Numpy, Pandas, datetime, Flask, gurobipy
