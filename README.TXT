INSTRUCTIONS
############

One typical feature of the software we make at Infront is the ability to perform technical analysis on financial instruments. One tool used for this purpose is 
to calculate certain functions on data presented in a chart and plot the result in the same chart. In this test we want you to calculate and plot two such
functions, Bollinger bands and the relative strength index.

1. Bollinger bands
Bollinger bands consists of three plot-lines, a 20 day (or other period, but we use 20 day in this test) moving average as the center band, and an upper and lower band
two standard deviations above and below the center band. Bollinger bands are typically plotted together with the original data.

Details about Bollinger bands and calculation can be found here: http://stockcharts.com/school/doku.php?id=chart_school:technical_indicators:bollinger_bands

2. The relative strength index.
The RSI is an indicator that measures the speed and change of price movements. RSI is typically plotted below the original data on a separate y-axis.

Details about RSI can be found here: http://stockcharts.com/school/doku.php?id=chart_school:technical_indicators:relative_strength_index_rsi

In the data/ folder there are historical prices for two stocks (Statoil on Oslo stock exchange and ABB on Stockholm stock exchange). Use these for your calculations. The file index.html is
a template that renders the provided data using the open source library Chart.js (http://www.chartjs.org/). You don't have to use this, but we do expect your solution to be implemented using
javascript or a language that compiles to javascript (typescript, coffeescript, etc.).

