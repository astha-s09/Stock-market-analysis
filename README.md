
# Stock Market Analysis

### Dashboard Link : https://app.powerbi.com/groups/me/reports/2fb7da43-9659-473a-baea-18dc1b753e79/ReportSection?experience=power-bi

## Problem Statement

This analysis delves into a comprehensive dataset focused on Stock market Analysis.The primary objective of this dataset is to provide insights into the stock market performance of the select major companies. Through analysis, we aim to identify patterns, trends, and anomalies in the stock’s behaviour over time. By doing so, we hope to make informed decisions regarding the stock purchases, sales, or holdings, potentially.


### Steps followed & kpi's

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.

- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.

- Step 3 : Visual filters were added for two fields named "Company", & "Year".

- Step 4 : one multi-row card visual were added to the canvas, Beta, Avg PE value, Avg market cap, Dividend amount.

- Step 5 : A line chart added to the report design area representing the Avg trading volume. 

- Step 6 : Treemap was used to represent Highest market cap.

- Step 7 : Donut chart was used to represent Most volatile stock.

- Step 8 : pie chart was used to represent Highest Dividend & lowest Dividend amount.

- Step 9 : clustered bar chart was used to represent Highest $ lowest P/E ratio.

- Step 10 : line chart was used to represent Stocks near 52 week high & low.

- Step 11 : cluster column chart was used to represent Stocks with strong by signals & strong selling signal.

- Step 12 : In the report view, under the insert tab, one text boxes were added to the canvas, project name was mention.


# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;


## Average Daily Trading Volume:
The average number of shares traded daily. High Trading volume indicates that a stock market is highly liquid. Liquidity refers to the ease with which assets can be bought or sold without significantly affecting their prices.

![Avg trading vol](https://github.com/astha-s09/Stock-market-analysis/assets/169142674/c7b121aa-7054-474b-afa0-98bec98258f8)

## Most Volatile Stocks:
Stocks with the highest Beta values. Stocks with the highest beta values typically indicate that they are more volatile and have higher price sensitivity to market movements compared to overall market Index.       

![volatile stock](https://github.com/astha-s09/Stock-market-analysis/assets/169142674/260bfe54-d263-4932-a025-0e7bbbf5772f)

## Stocks with Highest Dividend and Lowest Dividend:
Stocks that have provided the highest dividend amounts and lowest amounts. Stocks with low or no dividends are often associated with growth investing. Generally, companies reinvest their earnings to fund expansion, research and development, and other growth initiatives rather than distributing them to shareholders.        

![dividend amount](https://github.com/astha-s09/Stock-market-analysis/assets/169142674/35015527-2177-454c-b0cf-6c1ddb647533)
 
## Highest and Lowest P/E Ratios:
Identification of stocks with the highest and lowest Price-to-Earnings ratios. 

a) High P/E ratios are often associated with stocks that investors expect to have strong earning growth in the future. These stocks are often considered growth stocks. Investors are willing to pay a premium for these companies because they believe that their earnings will increase significantly.

b)Low P/E ratios are often associated with value stocks. These stocks are perceived as undervalued by the market, and investors and they may conceive that the current stock price does not reflect the company’s true worth


![PE ratio](https://github.com/astha-s09/Stock-market-analysis/assets/169142674/a1ab774f-1f04-4bac-a910-d8a479d0229a)
 
## Stocks with Highest Market Cap:
Companies with the largest marketcapitalizations. Stocks with the highest market cap offer stability and liquidity, they may not offer the same growth opportunities as smaller, high growth stocks. Market Cap is a measure of a company’s total market value. 

![market cap](https://github.com/astha-s09/Stock-market-analysis/assets/169142674/6b5d3e6c-f8f6-430f-9966-2a58a52d93b6)

## Stocks Near 52 Week High & Low:
Stocks Near 52 Week High: A stock's "52-week high" refers to the highest price at which a particular stock has traded over the past 52 weeks (one year). This metric is used by investors and traders to gauge a stock's recent performance and to assess its potential future movements.

Stocks Near 52 Week Low:  When a stock reaches its "52-week low," it means that the stock's price has dropped to its lowest level in the past 52 weeks (one year). Also stock reaching to 52-week low often reflects negative sentiment and a lack of confidence in the company's prospects. Investors may be selling their shares due to concerns about the company's financial health or other factors.

![stocks near 52 week](https://github.com/astha-s09/Stock-market-analysis/assets/169142674/3ef2bcd5-0cc3-448c-b24e-46b3655e7f8b)

## Stocks with Strong Buy Signals and stocks with Strong Selling Signal:
Using the MACD and RSI, stocks that are potentially good buys (e.g., MACD above signal line and RSI below 45) 
a) RSI below 45 indicates oversold market and a sign of potential buying opportunity because the stock or asset may be undervalued or oversold and there the probability is higher that price can bounce back. (Oversold market is one that has fallen sharply and expected to bounce higher) and RSI moves towards 80 it indicates overbought conditions. (Overbought market has risen sharply and is possibly ripe for a decline). Whenever RSI value is between 45 and 68 is often considered as a neutral zone, suggesting the stability in the price movements. Whenever RSI value is greater than or equal to 69 indicates overbought condition and a sign of potentially strong selling opportunity.

b) When the MACD value is greater than 0, it means that the stock’s short – term trend is bullish and this can be seen as a potential buying signal and when the MACD value is less than 0 indicates that stock short term trend is bearish and it can be seen as a Potential selling signal or shortening signal.

![strong signal](https://github.com/astha-s09/Stock-market-analysis/assets/169142674/e87716ec-6383-44b2-8330-ad9a1e9e2a09)

# Snapshot of Dashboard (Power BI Service)

![services](https://github.com/astha-s09/Stock-market-analysis/assets/169142674/862e15e4-7b07-4b74-89df-bd655d6ff2b1)
 
# Report Snapshot (Power BI DESKTOP)

![dashboard](https://github.com/astha-s09/Stock-market-analysis/assets/169142674/2091b131-c91d-46be-85bc-4cdefe7d0f1d)


