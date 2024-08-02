# Fractality-quant-test

Implement Any one of the simple strategy below using python or other languages you prefer: 

# Stragey 1: Momentum based long only
* Tokens candiates: with top 50 Marketcap, remove the stable coin, and filtered by token with top 30 trading volume. (such data can be easily get using coingecko or other public sources).
* position allowed: either long token, or park as USDT (or other stable coin you like)
* Signal: choose any one you like.
* Benchmark: use BTC hold in the whole period
* Backtest period: past 1 year good enough. if you have longer history, better.
* Evaluation criteria: Total return, sharpe ratio, maximum drawdown, drawdown recover period
* Addon: anything you think that are useful.

# Stragey 2: Momentum based but with long-short
* similar as strage 1, only changed part is you can either long or short tokens.
* Positions allowed: long, short, or park cash.
* price data: you can using token data direct for long or short. (meaning ignore the spread of spot, futures for simplicity)

# Stragey 3: Mean reversion based
* similar as strage 1 /2 , only if you prefer mean-reversion rather than momentum


Time allowed: 7 days. 
Action: choose any Strategy you like and code it out. 
Results to submit: code + a simple report 
