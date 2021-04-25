# Unit 5 - Financial Planning


## Background

For homework 5/APIs, we were asked to analzye a hypothetical portfolio of crytocurrency (1.2 shares of BTC and 5.3 shares of ETH), 200 of US Aggregate Bond ETF (ticker: AGG), and 50 shares of the SPDR S&P 500 ETF. 

We were given a starter code file which dicated the structure of this program as well as variable types and names. 

## Part 1 -- Personal Financial Planner

The first part of this homework required: 

1. Obtaining prices for cryptocurrencies using pricing data from https://alternative.me/crypto/ and the python requests library and json 
2. Obtaining prices for AGG and SPY using alpaca. 

The pricing data was used to obtain the value of the portfolio by multiplyting the priced * shares owned.

The value of the portfolio was aggregated into two assets (crypto & shares) using a pandas dataframe named df_savings.

## Part 2 -- Retirement Planning

The second part of this homeword requried simulating returns of the portfolio over a thirty year period using the MC Simulation class. The assignment stipulated that the simulated portfolio mix be 60% SPY and 40% was made of AGG. There was no mention of a crypto allocation in the instructions or related image files and accordingly, I did not include crypto in the Monte Carlo simulation.   

## Bonus learning

The homework also included the option to simulate returns over a 5 year and 10 year period with a larger investment amount of $60,000 which served to illustrate that returns seen over shorter investing timeframes can be similar to longer timesframes if one is able to invest more. 

