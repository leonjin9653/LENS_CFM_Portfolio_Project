# LENS_CFM_Portfolio_Project
CFM Portfolio Project 

Rough Ideas:
Data: Industry/sector, market cap, beta/risk, volume,  correlation (covariance), pull momentum from past data, price std 


# Portfolio 1 - Low Risk (Safe)
Capital : $750 000
Number of stocks we are allowed to invest in is 10-20
Max weight in one sector is 40%
Max weight in one stock is 15%
Transaction fee : min($2.15,$0.001 per share)
Things to look for/possible strategies: 
Filter for large market cap stocks
Look for low std in past historical prices 
Filter for “safer” market sectors and diversify it so its 20% max per sector
E.g. Health care, utilities, consumer staples
Low beta (0.4-0.8)
5% max per stock (max out all stock spots)
Low interstock correlation (?) if possible 


# Portfolio 2 - High Risk (Growth)
Capital: $1 000 000
Objective: Highest expected return
Number: 10-20
Transaction fee : min($2.15,$0.001 per share)
Things to look for/possible strategies:
Tech sector, finance services, industrials, basic materials
Momentum of past 6 month price data (ADX)
Positive directional index above 30-ish (testable)
Lookback range 1-3 months (testable)
Smaller market cap firms 
High beta (1.3-2)
High Return on Equity (ROE) 
EPS? And looking at company debt and cashflow
Volume
Higher sector concentration (tech, energy)
Max out 40%? 
Larger individual ticker weightings 
ATR_average




### System Design (WIP)

# Tier 1
[ticker csv file]
|||||||||||||||||
[Initial filter for portfolio requirements]
|||||||||||||||||
[Download price data for filtered ticker list in 1 call, slice into individual dfs]
|||||||||||||||||
[Call indicator functions, append to individual ticker dfs]
|||||||||||||||||
[Bayesian hyperparameter optimization]
|||||||||||||||||
[Ticker indicator evaluation and sorting into Port A and Port B]
|||||||||||||||||
[Evaluation of individual ticker weightings and sector weightings]

# Tier 2
# Tier 3 


