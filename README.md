# EDA - Top Tech Companies Stock Price

![Python](https://img.shields.io/badge/Python-3.7.6-blue) ![License](https://img.shields.io/badge/License-Apache%202.0-orange) ![Contributions](https://img.shields.io/badge/Contributions-Welcome-green)

In this notebook we analyze a dataset call [Top Tech Companies Stock Price](https://www.kaggle.com/tomasmantero/top-tech-companies-stock-price), which you can find in Kaggle.

We will be analyzing companies from the technology sector. We will analyze their behaviors over the past few years, as well as their behaviors during the COVID-19 Pandemic.

We will try to determine new trends that can help investors make more informed decisions.

To see the Kernel directly from Kaggle click [here.](https://www.kaggle.com/tomasmantero/eda-top-tech-companies-stock-price-dataset)

**In this dataset you can find the Top 100 companies in the technology sector. You can also find 5 of the most important and used indices in the financial market as well as a list of all the companies in the S&P 500 index and in the technology sector.**

The [Global Industry Classification Standard](https://www.investopedia.com/terms/s/sector-breakdown.asp) also known as GICS is the primary financial industry standard for defining sector classifications. The Global Industry Classification Standard was developed by index providers MSCI and Standard and Poor’s. Its hierarchy begins with 11 sectors which can be further delineated to 24 industry groups, 69 industries, and 158 sub-industries.

You can read the definition of each sector [here.](https://www.msci.com/documents/1296102/11185224/GICS+Sector+definitions+Sept+2018.pdf/afc87e7b-bbfe-c492-82af-69400ee19e4f)

The 11 broad GICS sectors commonly used for sector breakdown reporting include the following:
Energy, Materials, Industrials, Consumer Discretionary, Consumer Staples, Health Care, Financials, **Information Technology**, Telecommunication Services, Utilities and Real Estate.

In this case we will focuse in the Technology Sector. **You can see all the sectors and industry groups [here.](https://www.bloomberg.com/markets/sectors)**

To determine which companies, correspond to the technology sector, we use Yahoo Finance, where we rank the companies according to their “Market Cap”. After having the list of the Top 100 best valued companies in the sector, we proceeded to download the historical data of each of the companies using the NASDAQ website.

Regarding to the indices, we searched various sources to find out which were the most used and determined that the 5 most frequently used indices are: Dow Jones Industrial Average (DJI), S&P 500 (SPX), NASDAQ Composite (IXIC), Wilshire 5000 Total Market Inde (W5000) and to specifically view the technology sector SPDR Select Sector Fund - Technology (XLK).  Historical data for these indices was also obtained from the NASDQ website.

## Content

In total there are 107 files in csv format. They are composed as follows:

- 100 files contain the historical data of tech companies. 
- 5 files contain the historical data of the most used indices. 
- 1 file contain the list of all the companies in the S&P 500 index.
- 1 file contain the list of all the companies in the technology sector.

## Column Description

Every company and index file has the same structure with the same columns:

- **Date:** It is the date on which the prices were recorded.
- **High:** Is the highest price at which a stock traded during the course of the trading day.
- **Low:** Is the lowest price at which a stock traded during the course of the trading day.
- **Open:** Is the price at which a stock started trading when the opening bell rang.
- **Close:** Is the last price at which a stock trades during a regular trading session.
- **Volume:** Is the number of shares that changed hands during a given day.
- **Adj Close:** The adjusted closing price factors in corporate actions, such as stock splits, dividends, and rights offerings.

The two other files have different columns names:

***List of S&P 500 companies***

- **Symbol:** Ticker symbol of the company.
- **Name:** Name of the company.
- **Sector:** The sector to which the company belongs.

***Technology Sector Companies List***

- **Symbol:** Ticker symbol of the company.
- **Name:** Name of the company.
- **Price:** Current price at which a stock can be purchased or sold. (11/24/20)
- **Change:** Net change is the difference between closing prices from one day to the next.
- **% Change:** Is the difference between closing prices from one day to the next in percentage. 
- **Volume:** Is the number of shares that changed hands during a given day.
- **Avg Vol:** Is the daily average of the cumulative trading volume during the last three months.
- **Market Cap (Billions):** Is the total value of a company’s shares outstanding at a given moment in time. It is calculated by multiplying the number of shares outstanding by the price of a single share.
- **PE Ratio:** Is the ratio of a company's share (stock) price to the company's earnings per share. The ratio is used for valuing companies and to find out whether they are overvalued or undervalued.

## Acknowledgements

[SEC EDGAR | Company Filings](https://www.sec.gov/edgar/searchedgar/companysearch.html)

[NASDAQ | Historical Quotes](https://www.nasdaq.com/)

[Yahoo Finance | Technology Sector](https://finance.yahoo.com/screener/predefined/ms_technology?offset=0&count=100)

[Wikipedia | List of S&P 500 companies](https://en.wikipedia.org/wiki/List_of_S%26P_500_companies)

[S&P Dow Jones Indices | S&P 500](https://www.spglobal.com/spdji/en/indices/equity/sp-500/#data)

[S&P Dow Jones Indices | DJI](https://www.spglobal.com/spdji/en/indices/equity/dow-jones-industrial-average/#data)

## Inspiration

Possible questions which could be answered are:

- **In the Top 100 Tech Companies, which are the most profitable companies?**
- **The presidential elections in the United States will be soon, do you think this will affect a particular company and if so, which would affect them more?**
- **Which are the companies that have benefited the most from the COVID-19 Pandemic?**

**[More Datasets](https://www.kaggle.com/tomasmantero/datasets)**

## License

This Notebook has been released under the Apache 2.0 open source license.
