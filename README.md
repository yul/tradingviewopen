# TradingView Open Source
Here is my open-source TradingView indicators and strategies

## OutOfTheNoiseIntradayWithVWAP.pine
This is my implementation of  "Beat the Market An Effective Intraday Momentum Strategy for S&P500 ETF (SPY)" paper by Carlo Zarattini, Andrew Aziz, Andrea Barbon
It is supposed to run on 30-minute timeframe, there may be issues on other timeframes

## IntrabarOpenCloseGap.pine
Just checking one idea: look at gaps between close and open bars on lower timeframe to try to estimate how much slippage exists there that may be a result of buying or selling pressure.
Perhaps it only useful in real time to see if situation of the current bar is changing.
