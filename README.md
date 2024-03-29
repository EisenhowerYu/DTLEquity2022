# DTLEquity2022

## Description
A code written on Python for my submission in the DTL Equity Research Challenge 2022. Data is taken from the yfinance API library, and processed through pandas, numpy and statsmodels.tsa.stattools. Attached is a .pdf containing the report, a .ipynb containing the program, an .xlsx file containing the financial statements analysis.

### How to Use
Simply run the .ipnyb file

In [1]: import relevant python packages  
In [2]: download price data  
In [3]: Price performance calculated as (End Price - Beg Price)/Beg Price  
In [4]: Checks correlation  
In [5]: Checks Pearson R Correlation  
In [6]: Checks cointegration. JPM-BAC pair is likely cointegrated  
In [7]: Checks stationarity. JPM is stationary as p-value is significantly higher than critical values  
In [8]: Spread calculated from Ordinary Least Squares  

> z_t = y_1t - γ * y_2t = mean + error_t (spread formula)  
> S2 = y_1t  
> S1 = y_2t  
> b = γ  
> Upper and lower bounds calculated from standard deviations away from mean  

In [9]: Z score of spread is calculated, upper and lower bounds represented in standard deviations  
In [10]: Pair trade system backtested on 2020-2021 data  
In [11]: Arbitrage opportunities from backtested data  
In [12]: Cumulative PnL resulting from arbitrage  

### Credits
Code and analysis by Eisenhower Yu, Ateneo de Manila University 3rd Year BS Management  
Cross-checked with Bruce Romualdez, Ateneo de Manila University 3rd Year BS Applied Mathemetics Finance
