# Fractality-quant-test

Please implement 2 simple strategy using python or other languages you prefer: 

# Stragey 1: Momentum based long only
* Tokens candiates: with top 50 Marketcap, remove the stable coin, and filtered by token with top 30 trading volume. (such data can be easily get using coingecko or other public sources).
* position allowed: either long token, or park as USDT (or other stable coin you like)
* Momentum signal: choose any one you like.
* Benchmark: use BTC hold in the whole period
* Backtest period: past 1 year good enough. if you have longer history, better.
* Evaluation criteria: Total return, sharpe ratio, maximum drawdown, drawdown recover period
* Addon: anything you think that are useful.

# Stragey 2: Momentum based but with long-short
* similar as strage 1, only changed part is you can either long or short tokens.
* Positions allowed: long, short, or park cash.
* price data: you can using token data direct for long or short. (meaning ignore the spread of spot, futures for simplicity)

Time allowed: 7 days. 
Results to submit: code + a simple report 
