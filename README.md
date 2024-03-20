# TradingView - Pine script #

## Cloud Legend ##
### TK Crosses Period ###
![image](https://github.com/harryguiacorn/tradingview/assets/1398153/22c72528-15b6-4488-bbbf-ee1b90b1e1f9)
* The Tenkan-sen (conversion line) and Kijun-sen (base line) indicate price momentum and potential trend changes. A Tenkan-sen crossover above Kijun-sen within the cloud suggests a medium-strength upward signal. Above the cloud, the signal strengthens, and below it, weakens.
* The TKx value in the top right panel shows the number of periods since the Tenkan-sen and Kijun-sen last crossed, which can provide an indication of the trend's strength and potential continuation.
* The top right panel shows the timeframe of the most recent crossovers for reference. Additionally, the current daily range compared to the Average True Range (ATR) can provide insights into momentum strength. An unusually large daily range compared to the ATR can indicate weakening momentum and potentially less fuel for the trend to continue.

## Kijun Arrow ##
This indicator places an arrow below or above the candlestick when the Kijun-sen changes direction. The remaining elements use standard Ichimoku Cloud settings. (see chart below)

![BRK B_2022-10-25_12-34-26](https://user-images.githubusercontent.com/1398153/197763143-523ed510-b02b-4715-bea4-472ceb90acdc.png)

## Quantity Quality Commitment (QQC) ##
The QQC aims to assess the underlying strength of momentum by examining three metrics: quantity, quality, and commitment. (see chart above)
* **Quantity**: This metric counts the number of bullish versus bearish candlesticks over defined periods.
* **Quality**: It measures the quality of bullishness versus bearishness in the candlesticks over defined periods. For example, if a bullish candlestick has minimal wicks, it indicates that the bulls maintained control from beginning to end, resulting in a high score for the bullish tally.
* **Commitment**: The previous two metrics can provide a false sense of direction if there is little volume. A lack of volume can lead to unstable momentum. Therefore, this element incorporates volume to provide a comprehensive view from three perspectives.
* **ADX**:  If the ADX is above 20, the market is considered to be in a trending environment. Otherwise, it's not in a trend, and price action is likely to be choppy. This indicator is presented in histogram format.

## ADX-Hist ##
![SPX_2022-11-07_21-32-38](https://user-images.githubusercontent.com/1398153/200420661-bf515be5-ee95-4ed1-bc74-687c7b496956.png)
* ADX is a tool for assessing the trendiness of a market. If the ADX is below 20, it indicates that recent price action has been choppy, and this is represented by grey bars in the histogram. However, if the ADX is above 20, the bars are coloured orange.

## HOLP-LOHP ##
![image](https://github.com/harryguiacorn/tradingview/assets/1398153/e9058a44-796b-4e56-a19f-188f74bd4a03)

### Setting Panel ###
![image](https://github.com/harryguiacorn/tradingview/assets/1398153/993e143a-179a-4df2-b1b3-28963eedb579)

* HOLP stands for **H**igh **O**f the **L**ow **P**eriod
* LOHP stands for **L**ow **O**f the **H**igh **P**eriod
* HOLP and LOHP are indicators based on concepts developed by John Carter in his book, "Mastering the Trade." Their purpose is to identify potential reversal points in a trading session.
* The fundamental concept is to identify the session's high and mark the low of the session high for a short entry, and vice versa for a long entry.
* The default lookback period is set to 10 in this indicator, but John Carter emphasized using experience and common sense rather than relying solely on a fixed number.

## Candlestick Kicker Pattern ##
![image](https://github.com/harryguiacorn/tradingview/assets/1398153/70af4b7f-000a-4424-be02-3bb274ee4498)

### Setting Panel ###
![image](https://github.com/harryguiacorn/tradingview/assets/1398153/af30c867-5442-4651-b5ec-7dfc70725856)

Few candlestick patterns inflict more pain on traders on the other side of the trade than this signal. When it occurs, think of it as a swift kick to the teeth; the pain is very real.

An upward signal is generated when you have a two-bar formation. The left candle is bearish, while the succeeding one is bullish. Both candles have fat bodies, meaning the open is close to the high, and the close is close to the low for the first candle. For the adjacent candle, the open is close to the low, and the close is close to the high. The other crucial condition is that the open of the first candle must be lower than the open of the latter one.

The downward signal is the opposite of the upward signal.

## Candlestick Inside Bar Pattern ##
![image](https://github.com/harryguiacorn/tradingview/assets/1398153/b9e1644c-74e0-4912-98dd-976b31989b60)

### Setting Panel ###
![image](https://github.com/harryguiacorn/tradingview/assets/1398153/7f1dad72-c15f-4a7e-ad12-5d8216d53d4e)

An inside bar pattern is a two-bar scenario in which the range of the second bar is contained within the range of the preceding one. This pattern typically occurs when market volatility is diminishing, and it often precedes an expansion in the price range, resulting in a breakout. A signal will be generated above or below the breakout candle when these conditions are met.

## Candlestick Engulfing Pattern ##
![image](https://github.com/harryguiacorn/tradingview/assets/1398153/5084b31c-b4fe-448b-8c97-12d82fbc6538)

### Setting Panel ###
![image](https://github.com/harryguiacorn/tradingview/assets/1398153/76eb0230-80ad-4088-96f4-f75fd76a0bd6)

This is a classic candlestick pattern that serves as a warning that the current trend may have come to an end or is pausing. In a bullish setup, the body of the second candle completely engulfs the body of the previous candle, and vice versa. There are options available for filtering based on the ratio of body size to the overall range for both candles.

## ATR warning ##
![image](https://github.com/harryguiacorn/tradingview/assets/1398153/a863e21d-167b-480b-8355-b8c8bd29acae)
An objective way to determine if a candle's range has exceeded its average candle ranges is by comparing it to its Average True Range (ATR). When market conditions become volatile, resulting in notably large candles, such moves are less likely to be sustained, which increases the likelihood of a return to a consolidation phase. This tool can assist traders in tightening their stop-loss orders to lock in potential profits when candles have extended beyond their average range.

At the bottom of the chart, a row of dots is displayed, with colours ranging from black to light grey. These dots indicate the range of the current candle in relation to its ATR. Darker dots signify that the candle's range is closer to the ATR, while lighter grey indicates that it's farther away. When a black dot is present, it signifies that the candle has moved beyond the ATR.

## Body Mass Indicator (BMI) ##
![image](https://github.com/harryguiacorn/tradingview/assets/1398153/1cd84a8f-5bc4-413e-845b-cf2dfead292d)
This indicator highlights candles with the largest bodies (the range between open and close) over the past 26 periods. While a bullish candle may have a substantial range (the difference between its high and low), it's a sign of weak bullishness if the bulls can't maintain their position until the candle's close. Conversely, the same principle applies to bearish candles. The goal is to provide users with insight into subtle shifts in the balance of power within price action or the potential for trend continuation amid the ongoing battles between bulls and bears.

## Bar Fractal by Tom Hougaard ##
![image](https://github.com/harryguiacorn/tradingview/assets/1398153/032ed252-7164-41f5-9a0c-904853ea2b90)

Source: (https://tradertom.com/wp-content/uploads/2021/04/Tom_Hougaard_The_Trading_Manual_Singles.pdf)

>There are 2 conditions to the technique.

>**Buy Signal**

> The CLOSE of the current bar (1) must be higher than the HIGH of the previous bar (2).
> The CLOSE on this bar (1) must be higher than the HIGH of the bar three bars back (4).
> 3 If those conditions are met, we have a BUY SIGNAL.

>**Sell Signal**

> The CLOSE of the current bar (1) must be lower than the LOW of the previous bar (2).
> The CLOSE on this bar (1) must be lower than the LOW of the bar three bars back (4).
> 3 If those conditions are met, we have a SELL SIGNAL.

## Bollinger Bands Force (BBForce) ##
![SPX_2022-11-04_21-18-11](https://user-images.githubusercontent.com/1398153/200076350-e9a4cb3b-334c-485e-9b4f-d881f478a3de.png)
* Bollinger Bands consist of three components: a simple moving average with +2 and -2 standard deviation lines above and below. When all three components align in the same direction, a Bollinger Bands Force arrow is displayed on the chart, indicating that the forces are in agreement. The default setting for the moving average has been adjusted to 26, instead of the standard 20.
* Fuchsia arrows are displayed whenever the three aforementioned components are in sync.
* Yellow arrows represent a minimal version that only indicates a change in direction among these three components.

## Disclaimer ##
The content and materials are for your information and education only and not financial advice or recommendation.
