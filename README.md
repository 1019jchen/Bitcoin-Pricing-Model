# Bitcoin Pricing Model

## Information on the Data:

All the data used is from the following sources:
- Bitcoin Data (contains information on opening, closing prices and returns): https://www.investing.com/crypto/bitcoin/historical-data

The Bitcoin Data is the variable that we wish to model and predict better with the other information provided.


- Google Trend Data (trends for: cryptocurrency, bitcoin, and blockchain): https://trends.google.com/trends/


The Google Trend Data is meant to paint a better picture of how social network effects and investory curiosity can drive Bitcoin returns.

- Federal Reserve Data: https://fred.stlouisfed.org/series/

From the Federal Reserve Data, we used the following datasets:

Daily Market Indicators:
- CBOE Volatility Index: VIX (VIXCLS), to track market volatility
- ICE BofA US High Yield Index Total Return Index Value (BAMLHYH0A0HYM2TRIV), to track the performance of high-yield debt (junk bonds
- S&P 500 (SP500), to track general performance of the stock market
- 10-Year Treasury Constant Maturity Minus 2-Year Treasury Constant Maturity (T10Y2Y), to track the risk premium associated with holding long-term assets


Monthly Economic Indicators:
- Unemployment Rate (UNRATE), to track the relationship between economic distress and cryptocurrency
- M2 (WM2NS), to track money in the US economy and the general buying power of the public
- Federal Funds Effective Rate (FEDFUNDS), to track the general trend of interest rates in the economy
