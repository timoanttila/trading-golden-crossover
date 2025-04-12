# The Golden Crossover

An exponential moving average (EMA) is a type of moving average that gives more weight to recent price data, making it more responsive to price changes compared to a simple moving average (SMA). Moving averages are widely used by traders to identify trends, reversals, and potential entry or exit points in the market. The script plots three EMAs with different periods to capture short-term, medium-term, and long-term trends.

[Golden Crossovers](./GoldenCrossover.pine) is a Pine Script indicator for TradingView that highlights potential bullish and bearish signals based on moving average crossovers.

I mainly use this strategy on 5-minute Forex charts. It performs well in trending markets but can give false signals during choppy or sideways conditions. I only take trades in the direction of the long-term trend. For bullish setups, the price should be above the Long SMA; for bearish setups, it should be below the Long SMA.

You can customize the Short, Medium, and Long periods. I personally use 13, 48, and 200.

I don't recommend entering a trade immediately after a crossover. It's better to watch how the price reacts. The safest entry is when the price pulls back to the Short EMA and bounces off it—ideally with a candle that shows a long wick against the trend direction, signaling rejection.

Every trade should aim for at least a 1:1 risk/reward ratio. I recommend using a tight stop-loss and letting your winners run until the price closes on the other side of the Medium EMA or a new crossover occurs.

Only risk a maximum of 1% of your trading account per trade idea. If you take two losses in one day, stop trading for the day. This helps you avoid revenge trading and emotional decisions. Always move your stop-loss to break-even or under/above the latest pullback once the price is in profit. This way, you can avoid losing trades and let your winners run longer.

You can add a new position if the trade is in profit and the price bounces off the Short EMA again. This is called "scaling in" and can help you increase your position size while managing risk. A new position should only be taken after the original one is at break-even or in profit.

### Bullish arrow

- Short crosses above Medium.
- Short and Medium are above Long.

### Bullish triangle

- Short crosses above Long.
- Short is above Medium.

### Bearish arrow

- Short crosses below Medium.
- Short and Medium are below Long.

### Bearish triangle

- Short crosses below Long.
- Short is below Medium.

## Read more

- [Golden Cross Pattern Explained With Examples and Charts](https://www.investopedia.com/terms/g/goldencross.asp)
- [Golden and Death Crosses Explained](https://finance.yahoo.com/news/golden-death-crosses-explained-080044428.html)
- [Study determines the best moving average crossover trading strategy](https://finance.yahoo.com/news/study-determines-best-moving-average-195042216.html)
- [Moving Average (MA): Purpose, Uses, Formula, and Examples](https://www.investopedia.com/terms/m/movingaverage.asp)