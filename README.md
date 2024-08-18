# Fractality-quant-test

# Purpose: 
* Note that this is NOT a test of coding skills. It is a test of whether you can find meaningful insights in the market gives us an edge.
* If you already have an idea on how to achieve this, you can based on it and do a simple backtest.
* If you do not any your own idea, then you can pick up just one algorithm below and test to find insights (it can be a specific value of a paramter than can increase the success rate, the expected return, or a method for detecting a pair better than common online material, or any other things).
* After you done the coding, please provide simple comments on it assumptions or when/where will it work/or not.

# strategy 1: Momentum based long only
* Token candidates: with top 50 Market Cap, remove the stable coin, and filtered by token with top 30 trading volume. (such data can be easily get using coingecko or other public sources).
* position allowed: either long token, or park as USDT (or other stable coin you like)
* Signal: choose any one you like.
* Benchmark: use BTC hold in the whole period
* Backtest period: past 1 year good enough. if you have a longer history, better.
* Evaluation criteria: Total return, sharpe ratio, maximum drawdown, drawdown recovery period
* Addon: anything you think that is useful.

# strategy 2: Momentum based but with long-short
* similar to strategy 1, the only changed part is you can either long or short tokens.
* Positions allowed: long, short, or park cash.
* price data: you can use token spot price data directly for long or short. (meaning ignore the spread of spot, futures for simplicity)

# strategy 3: Mean reversion based
* similar as strategy 1 /2 , only if you prefer mean-reversion rather than momentum


# Timeline and Results:
* Time allowed: 7 days. 
* Action: choose any strategy you like and code it out. 
* Results to submit: code + a simple report 
