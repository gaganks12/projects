# Addictive Time series Model

Addictive Time series Model for Tesla, ford and gm using historical dataset. 
forecasting overall trend along with different scales such as daily, weekly, seasonally and yearly using facebooks
prophet open source library.

Forecast is performed on market cap values of Tesla, GM and Ford.

Comparing the stockprice of the stocks/companies is not sufficient to tell the value of the company, number of shares also contributes to the market cap of the company. 

## Caluclate Market cap

Market cap= adj.close * number of shares

Above formula is used to caluclate market cap of all three stocks.

## Number of shares of all three companies 

tesla_shares = {2018: 171, 2017:166 , 2016: 144, 2015: 128}

gm_shares = {2018:1431 , 2017:1492 , 2016: 1570, 2015: 1640}

ford_shares={2018: 3998, 2017:3998 , 2016: 3999, 2015: 4002}

## Results

1. Analysing the period of dominance of t_esla over G_M and f_ord

2. Checking overall trend along with daily, seasonally and yearly

3. forecating for next 3 years


## Requirements

Python 3.6+
numpy
pandas
matplotlib
prophet

## Reference
https://www.macrotrends.net/stocks/charts/TSLA/tesla/market-cap

