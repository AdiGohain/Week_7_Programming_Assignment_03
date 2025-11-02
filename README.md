# Week_7_Programming_Assignment_03

This goal of this project is to develop a program for automated, algorithmic trading and to backtest my trading strategy. 

For this project, trading does not involve machine learning. Nor does it involve market regime detection. The minimum trading strategy for this project would be a simple mean-reversion or momentum model applied to the assets included my fund's portfolio. Focusing on automated trading itself. 

I employ thorough backtesting of my approach and metrics such as the Sharpe ratio to judge fund returns relative to their volatility.  Evaluate my fund's performance against a buy-and-hold baseline benchmark with 
(1) the S&P 500 using SPY ETF
(2) a market-cap-weighted index of non-financial NASDAQ-listed stocks like QQQ
(3) a US Treasuries, aggregate bond, or fixed-income fund.

<img width="1156" height="654" alt="image" src="https://github.com/user-attachments/assets/24666745-f62e-4ab2-8488-154a7f61769b" />

Use of AI in this Project:
I utilized ChatGPT for troubleshooting a method for calculating the cumulative exposure. Due to a Binary signal, I wanted to find better ways to visualize the data and I used ChatGPT to provide suggestions.

I also referenced the code provided by 
Clenow, Andreas F. 2019. Trading Evolved: Anyone Can Build Killer Trading Strategies in Python. Independently Published. [ISBN-13: 978-1091983786]
I used this code and incorporated the equities and commodities I wanted to test with.

The user can download the .ipbyn file and run the project. The algorithmic process has been automated to ingest data, run calculations and output graphs.
Libraries used: Pandas, Numpy, YFinance, and Matplotlib. 
