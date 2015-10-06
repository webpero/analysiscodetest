INSTRUCTIONS
############

One typical feature of the software we make at Infront is the ability to perform technical analysis on financial instruments. One tool used for this purpose is 
to calculate certain functions on data presented in a chart and the plot the result in the same chart. In this test we want you to calculate and plot two such
functions, Bollinger bands and the relative strength index.

1. Bollinger bands
Bollinger bands consists of three plot-lines, a 20 day (or other period, but we use 20 day in this test) moving average as the center band, and an upper and lower band
two standard deviations above and below the center band. Bollinger bands are typically plotted together with the original data.

Details about Bollinger bands and calculation can be found here: http://stockcharts.com/school/doku.php?id=chart_school:technical_indicators:bollinger_bands

2. The relative strength index.
The RSI is an indicator that measures the speed and change of price movements. RSI is typically plotted below the original data on a separate y-axis.

Details about RSI can be found here: http://stockcharts.com/school/doku.php?id=chart_school:technical_indicators:relative_strength_index_rsi

In the data/ folder are historical prices for two stocks (Statoil on Oslo stock exchange and ABB on Stockholm stock exchange). Use one or both of these for your calculations.
Submit your solution using a platform and language of your choosing (but be prepared to defend your choice if you choose something weird :) ). Feel free to use a library to draw
your charts.

Finally, answer these questions:
- There are about 500 datapoints in each file in this test. What would you do differently if there were 30000 datapoints.
- How would you accomodate real time streaming updates to the dataset.