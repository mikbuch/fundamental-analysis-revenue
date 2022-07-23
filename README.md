# Visualizing fundamental analysis indicators for NASDAQ companies

Fundamental analysis basics -- plotting a "revenue" indicator with Python.

This repository contains materials for [my article at Medium](https://medium.com/@mikolaj.buchwald/visualizing-fundamental-analysis-indicators-for-nasdaq-companies-in-python-cfebf8ad6191). Please, refer to [the article](https://medium.com/@mikolaj.buchwald/visualizing-fundamental-analysis-indicators-for-nasdaq-companies-in-python-cfebf8ad6191) for more information about the contants of the Jupyter Notebook available in this repository.

---

There are two main types of stock market analysis: technical analysis, and fundamental analysis. The former is what you may be more familiar with: the task of the technical analysis is to predict the future prices of a stock given its historical values and volume. On the other hand, the aim of the fundamental analysis is to determine "real" or "fair market" value of the stock, given company's financial condition, it's assets, market potential, etc.

![AAPL revenue graph](https://raw.githubusercontent.com/mikbuch/fundamental-analysis-revenue/main/images/aapl.png?token=GHSAT0AAAAAABU6Q5VDXP3XIHSH5Y2SJNQUYW4BTHQ)

For the more detailed definitions, see the excerpt from the [Investopedia article](https://www.investopedia.com/terms/f/fundamentalanalysis.asp) below:

> Fundamental analysis (FA) is a method of measuring a security's intrinsic value by examining related economic and financial factors. Fundamental analysts study anything that can affect the security's value, from macroeconomic factors such as the state of the economy and industry conditions to microeconomic factors like the effectiveness of the company's management.
>
> ...
>
> This method of stock analysis is considered to be in contrast to technical analysis, which forecasts the direction of prices through an analysis of historical market data such as price and volume. 
>
> ...
>
> * Fundamental analysis is a method of determining a stock's real or "fair market" value.
> * Fundamental analysts search for stocks that are currently trading at prices that are higher or lower than their real value.
> * If the fair market value is higher than the market price, the stock is deemed to be undervalued and a buy recommendation is given.
> * In contrast, technical analysts ignore the fundamentals in favor of studying the historical price trends of the stock.

Source: [Investopedia definition](https://www.investopedia.com/terms/f/fundamentalanalysis.asp)

---

In this Jupyter Notebook we will visualize fundamental analysis indicator data in Python. We will focus on the company revenue data, which we will obtain from the NASDAQ data portal ([data.nasdaq.com/databases/SF1/data](https://data.nasdaq.com/databases/SF1/data)).
