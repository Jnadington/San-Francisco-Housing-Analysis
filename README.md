# San Francisco Housing Market Analyzer
Analyzing housing and rent patterns in San Francisco area to identify proiftable real estate opportunities. Allows user to adjust neighborhood view on interactive map and to hover over areas for additional information. New feautures added as needed. Run on jupyterlab.

--- 

## Technologies

This project leverages Python 3.7 and Jupyter Lab with the following packages:

* [Pandas] (https://github.com/pandas-dev/pandas) - To create and manipulate dataframes
* [Bokeh] (https://github.com/bokeh/bokeh) - Used to create interactive map 
* [HVPlot] (https://github.com/holoviz/hvplot) - Used to create visuals for data analysis

(Import code blocks included in application)

--- 

## Installation Guide

Before running the application, first install the following dependencies 

```python
  pip install pandas
  pip install bokeh
  pip install hvplot
```

---

## Usage

To use the Algo Trading Project application, clone the repository and run the **housing_analysis.ipynb** on Jupyter Lab. 

--- 

## Examples

Upon running the inital code for yfinance data, you will asked to input a stock ticker for data.

![Yfinance Data Prompt](Images/Yfinance_Data.PNG)

Input in the following format 

![Yfinance Data Prompt Complete](Images/Yfinance_Data2.PNG)



The following code will display a candlestick chart with 8/13/21 EMA's, ADX, and Volume. Must run all code blocks beforehand for this to display properly.

![Candlestick Created](Images/Candlestick_Display.PNG)




After running the implement_ema_strategy function, running the following code will prompt you with a Take Profit % and Stop Loss %. Set these according to your preferences to backtest your algo against historical data. Also adds the buy_price, sell_price, and ema_signal (whether trade meets criteria) to dataframe.

![TP and SL](Images/tp_stoploss.PNG)



The following code prints the hvplot line chart that displays entry and exit points against historical data. 

![TP and SL](Images/backtest_chart_code.PNG)

![EntryExit Chart](Images/entry_exit_chart.PNG)



After running all previous code, the following code gives us the results of the Algo trade by compounding % return and starting with 100000 as the initial investment.

![Backtest Results](Images/backtest_results.PNG)

---








