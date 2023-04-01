# Financial_Planning_Tools
Part  1 of this app is a personal financial planner for emergencies which will enable credit union members to visualize their current saving and then determine if they have enough reserves for an emergency fund.Part 2 of the app is  financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years  and 10 years respectively. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.


## Methodology and Approach
Make API calls by using the Python Requests library and SDKs to get current data.

Use environment variables to protect private API credentials.

Apply the statistical concept of confidence intervals to measure the likelihood of future events, like the performance of an asset.

Build and run Monte Carlo simulations to evaluate the long-term future performance outcomes for portfolios.

## Libraries and Technologies Used

-Pandas library -  a Python library for data analysis. 

-Matplotlib - a Python plotting library for vusualizations  

-Jupyter notebook

-NumPy- for numrical computational tools.

-MCForecastTools  used to build and run  Monte Carlo simulations. 

Alpaca_trade_api  to get current data of stocks and bonds.

## Summary of findings 
By deploying the personal financial tool  the results showed that an average  credit union  member’s total portfolio of stocks and bonds is large enough to fund the emergency portfolio.

An evaluation of the long-term futute performance outcones for the  retirement portfolio  using financial planner for retirement  established that by  weighting the portfolio more heavily toward stocks than bonds,  credit union members  can  retire after only 10 years instead of 30 years. 

