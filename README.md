# Quantum Portfolio Optimizer

This is a concept idea for a Portfolio Optimizer using Quantum Optimization techniques such as use of QAOA and VQE optimization algorithms 
to make an end-to-end project that analyzes our user's current portfolio and based on their assets, their valuation and their percentages in
each sector and ticker, analyzes the risk percentage and returns and advices the user to restructure their portfolio to maximize returns and
minimize risks. We are trying to implement a model that would allow the user to decide their own comfortable risk levels, and based on those
risk levels, the model will try to maximize user profit percentage.<br> 

**Note:** This QPO is designed specifically keeping in mind a clientele who wish to use it for Long and Medium term investments and wish 
 to optimize their portfolio accordingly. Due to the complexities involved with real-time DB updation, computational costs, and precautions 
 and lack of infrastructure required to give real time results as a part of High Frequency Trading (HFT) techniques. This project is not built 
 with Intraday trading rapid restructuring in mind. This however remains a lucrative idea to us and has been considered for future scope of the
 project<br>


The goal of this project is to use a Classical Model to form a baseline and then use QAOA, which is a special case of VQEs to form a quantum
model that will predict the optimal risk, current risk, and advise the users to restructure their portfolios accordingly. The QPO will take 
user's current portfolio and store it, and perform operations on it and compare it with a Classical Baseline and give the user the results, 
as well as store it in a table. The metrics for every single account will be recalculated everyday using EOD prices fetched using APIs like
yfinance, and updated in the table.<br>

**Note:** The platform is only for analysis and restructuring suggestions, and will not be performing any trades by itself. The suggested 
changes should be carried out manually at user descretion.<br>

As of now, the platform will not be directly connected with the users demat account, and hence, any changes made to the portfolio should 
be updated by the user on the platform by logging into their accounts in order for the QPO to give accurate and useful results.<br>

The QPO also features a continous monitoring feature, in which all the metrics wll be recalculated and updated for each account daily using
EOD Prices of the applicable tickers. This feature is introduced to provide the user with an alert to restructure their portfolio once the
protfolio drift goes beyond a certain risk threshold. We also plan on sending users with regular remainders to update or view their 
portfolios so that they can get the latest suggestions based on the current market situation.<br>

This QPE will make use of properties of Quantum Computers to find hidden correlations which classical models may miss, hence providing a 
better insight into their portfolio management. The model will be capable of suggesting downsizing or upscaling the portfolio with certain 
stocks and their quantities. It will also be able to provide better results by checking the portfolio list and checking the correlation 
between two or more tickers and if they move in-sync, opposite or independent of each other. This gives a major advantage by identifying and 
preventing Sector Overexposure and correlated volatility of the tickers.

Lastly, this project is a brainchild of two very bored almost-engineers, late nights, lethal amounts of caffeine, and the sheer will
do tackle on a real world problem. This README file will be updated in a better and a more structured manner as we proceed further down 
the road. Godspeed!
