# TradingView
## Language - Pine script ##

![BRK B_2022-10-25_12-34-26](https://user-images.githubusercontent.com/1398153/197763143-523ed510-b02b-4715-bea4-472ceb90acdc.png)

### Kijun Arrow ###
This indicator paints an arrow below or above the candlestick when Kijun-sen changes to a new direction.
### Quantity Quality Commitment (QQC) ###
The QQC aims to gauge the underlying strength of momentum by looking at 3 metrics: quantity, quality and commitment.
* **Quantity**: a tally of bullish versus bearish candlesticks for defined periods.
* **Quality**: the quality of bullishness versus bearishness in the candlesticks for defined periods, e.g. if a bullish candlestick has little wicks, it signifies the bulls are in control from beginning to end, hence get a high score for the bull's tally.
* **Commitment**: the prior two metrics can send out a false sense of direction if there’s little volume, as lack of volume builds an unsteady momentum, therefore, this element takes the volume into the equation to paint a final picture from 3 aspects.
* **ADX**: if ADX is above 20, it's deemed to be in a trendy environment, otherwise it's not trendy and the price action would likely be choppy; this indicator is shown in histogram format. 

### Bollinger Bands Force ###
![SPX_2022-11-04_21-18-11](https://user-images.githubusercontent.com/1398153/200076350-e9a4cb3b-334c-485e-9b4f-d881f478a3de.png)
The Bollinger Bands are formed of 3 elements: a simple moving average with +2 and -2 Standard deviation lines above and below. When all three are stepping into the same direction, a Bollinger Bands Force arrow is printed on the chart denoting the forces are all in line. The default setting of the moving average has been modified to 26 rather than 20.
The fuchsia arrows are printed whenever aforementioned 3 elements are in sync.
The yellow arrows are the minimal version which only shows the change of direction in those 3 elements.
