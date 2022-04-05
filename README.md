# 5-challenge
Building a tool to help credit union members evaluate their financial health; assess their monthly budgets &amp; forecast a reasonably effective retirement plan based on their current holdings


## Technologies
This project uses Python 3.7.11 with the following packages & dependencies:
* import os
* import requests
* import json
* import pandas as pd
* from dotenv import load_dotenv
* import alpaca_trade_api as tradeapi
* from MCForecastTools import MCSimulation


## Installation
Using the Conda package manager: [GitHub](https://github.com/ALovettII/5-challenge.git)

You will also the following packages:
```bash
# Install json
conda install -c jmcmurray json

# Install Requests
conda install -c anaconda requests
```

Finally, ensure you have API credentials for the following: 
* [Alpaca](https://alpaca.markets) 

## Usage
# Set your monthly income
monthly_income = <income_of_your choosing>

Upon running the application, it will calculate the BTC (BTC & ETH) & portfolio holding (AGG & SPY) current value. Following which, using your monthly income and current holdings balance, the program will assess your emergency fund status - checking to see if there's enough money to satisfy three months of income. Finally, using this data, a Monte Carlo simulation is displayed showing current portfolio predictions. 

## Contributors
Created by Arthur Lovett