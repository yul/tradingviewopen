# TradingView Open Source
Here is my open-source TradingView indicators and strategies

## DailySeasonality.pine
This indicator calculates average returns for trading days across specified number of years in the past and displays this as a histogram. In addition, it displays EMA of these values as filled area plot.
Indicator uses ordinal number of trading day in a year, i.e. January 3rd may be 1st trading day, January 4th - 2nd trading day, etc.
Large green or red areas may mean that there is a strong seasonal factor at these dates that may support, launch, or break a trend.
It only works on daily timeframe at the moment. Maximum number of years it can look back is 15.

[![Daily Seasonality](https://github.com/user-attachments/assets/65325772-e648-4d7e-9f27-ec628eefa9bc)](https://www.tradingview.com/script/3PsyHq5G-Daily-Seasonality-YuL/)

## OutOfTheNoiseIntradayWithVWAP.pine
This is my implementation of  "Beat the Market An Effective Intraday Momentum Strategy for S&P500 ETF (SPY)" paper by Carlo Zarattini, Andrew Aziz, Andrea Barbon
It is supposed to run on 30-minute timeframe, there may be issues on other timeframes

[![NoiseChart](https://github.com/user-attachments/assets/f72201ad-6172-495d-81b5-d9d993d9c65f)
![NoisePlot](https://github.com/user-attachments/assets/1703f6e8-66df-491e-9b7b-7f597909936b)
](https://www.tradingview.com/script/gJeM3LZ5-Out-of-the-Noise-Intraday-Strategy-with-VWAP-YuL/)

## IntrabarOpenCloseGap.pine
Just checking one idea: look at gaps between close and open bars on lower timeframe to try to estimate how much slippage exists there that may be a result of buying or selling pressure.
Perhaps it only useful in real time to see if situation of the current bar is changing.

[![OpenCloseGapIntrabar](https://github.com/user-attachments/assets/00709a45-c9a2-41a0-a844-da0a5dc04bcb)
](https://www.tradingview.com/script/hGCF4lyJ-Intra-bar-Close-Open-Gap-YuL/)
