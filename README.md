# CandleStick 3 Candle Engulf

This code is a custom indicator for the MetaTrader 5 platform (mql5) that identifies bullish and bearish engulfing patterns in candlestick charts. It marks these patterns with lines on the chart, making it easier for traders to identify potential reversal signals.

## How it works

The indicator uses two main functions, `IsBullishEngulf` and `IsBearishEngulf`, to check for bullish and bearish engulfing patterns, respectively. These patterns occur when the current candle's open and close prices completely engulf the previous two candles. 

For a bullish engulfing pattern, the conditions are:
- The close price of the current candle is higher than the open price.
- The close price of the current candle is higher than the close price of the previous candle.
- The open price of the current candle is lower than the open price of the previous candle.
- The close prices of the previous two candles are lower than their respective open prices.

For a bearish engulfing pattern, the conditions are:
- The close price of the current candle is lower than the open price.
- The close price of the current candle is lower than the close price of the previous candle.
- The open price of the current candle is higher than the open price of the previous candle.
- The close prices of the previous two candles are higher than their respective open prices.

The indicator buffers are used to store the high and low values of the engulfing candles, which are then displayed on the chart as lines.

## Product Description

This code sample is provided by Forex Robot Easy Team. Forex Robot Easy is not the official developer of this product but showcases sample code that can work as described in the product.

The CandleStick 3 Candle Engulf indicator is designed to help traders identify potential bullish and bearish engulfing patterns in candlestick charts. These patterns are often considered reversal signals, indicating a potential change in market direction.

Key Features:
- Easy to use and install on MetaTrader 5 platform.
- Marks bullish engulfing patterns with a line on the chart.
- Marks bearish engulfing patterns with a separate line on the chart.
- Helps traders identify potential reversal signals in candlestick charts.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - CandleStick 3 Candle Engulf Review](https://forexroboteasy.com/forex-robot-review/candlestick-3-candle-engulf-unbiased-review-on-forex-software/).

Please note that Forex Robot Easy is not the official developer of this product. To find the official developer and obtain the complete version of this indicator, please visit the MQL5 marketplace.
