# TradingView
## Language - Pine script ##

![BRK B_2022-10-25_12-34-26](https://user-images.githubusercontent.com/1398153/197763143-523ed510-b02b-4715-bea4-472ceb90acdc.png)

### Kijun Arrow ###
This indicator paints an arrow below or above the candlestick when Kijun-sen changes to a new direction. The rest of the elements are bog-standard Ichimoku Cloud settings.
### Quantity Quality Commitment (QQC) ###
The QQC aims to gauge the underlying strength of momentum by looking at 3 metrics: quantity, quality and commitment.
* **Quantity**: a tally of bullish versus bearish candlesticks for defined periods.
* **Quality**: the quality of bullishness versus bearishness in the candlesticks for defined periods, e.g. if a bullish candlestick has little wicks, it signifies the bulls are in control from beginning to end, hence get a high score for the bull's tally.
* **Commitment**: the prior two metrics can send out a false sense of direction if there’s little volume, as lack of volume builds an unsteady momentum, therefore, this element takes the volume into the equation to paint a final picture from 3 aspects.
* **ADX**: if ADX is above 20, it's deemed to be in a trendy environment, otherwise it's not trendy and the price action would likely be choppy; this indicator is shown in histogram format. 

### Bollinger Bands Force (BBForce) ###
![SPX_2022-11-04_21-18-11](https://user-images.githubusercontent.com/1398153/200076350-e9a4cb3b-334c-485e-9b4f-d881f478a3de.png)
* The Bollinger Bands are formed of 3 elements: a simple moving average with +2 and -2 Standard deviation lines above and below. When all three are stepping into the same direction, a Bollinger Bands Force arrow is printed on the chart denoting the forces are all in line. The default setting of the moving average has been modified to 26 rather than 20.
* The fuchsia arrows are printed whenever the aforementioned 3 elements are in sync.
* The yellow arrows are the minimal version which only shows the change of direction in those 3 elements.

### ADX-Hist ###
![SPX_2022-11-07_21-32-38](https://user-images.githubusercontent.com/1398153/200420661-bf515be5-ee95-4ed1-bc74-687c7b496956.png)
* ADX is a tool for gauging trendiness, if ADX is under 20 it communicates to the traders that the recent price action has been choppy and shown as grey bars in histogram, otherwise if it’s above 20 the bars are painted orange.

### HOLP-LOHP ###
![SPX_2022-11-07_22-19-19](https://user-images.githubusercontent.com/1398153/200427563-f9629a58-97ab-4848-aea4-00651c1cfc9e.png)
* HOLP stands for **H**igh **O**f the **L**ow **P**eriod
* LOHP stands for **L**ow **O**f the **H**igh **P**eriod
* This indicator is based on John Carter’s HOLP and LOHP from Mastering the Trade. The basic idea is to identify the session high and mark the low of the session high for a short entry, and vice versa for a long entry.
* The default look back period is set to 10 here, albeit John Carter didn’t specify a hard coded number but rather the use of experience and common sense.

### Candlestick Kicker Pattern ###
Not many candlestick patterns hurt traders on the other side of the trade more than this signal, when it happens, think of it as kicking in the teeth, the pain is real.

An upwards signal is painted when you have a two-bar formation, the one on the left is a bearish one whereas the successive one is bullish, when you have fat bodies in both candles, meaning the open is close to the high and the close is close to the low for the first candle, while the open is close to the low and the close is close to the high for the adjacent candle , the pain is ever more excruciating, the other important condition is the open of the first candle must be lower than the open of the latter one.

The downwards signal is vice versa of the upwards signal.

### Disclaimer ###
The content and materials are for your information and education only and not financial advice or recommendation.


