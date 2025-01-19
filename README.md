# Sales Forecasting for Global Mart

### Tech Stack
Programming Languages: Python <br>
ML and Forecasting: Time Series Forecasting (Smoothing and Autoregressive Methods), Data Analysis

## Business Understanding
Global Mart is an online supergiant store that has worldwide operations. This store takes orders and delivers across the globe and deals with all the major product categories — consumer, corporate and home office.
As a sales manager for this store, we have to forecast the sales of the products for the next 6 months, so that we have a proper estimate and can plan wer inventory and business processes accordingly.


## Variables
The data consists of 7 different geographical market segments and 3 major customer segments.

### `Market Segment`
- Africa - Consumer
- APAC (Asia Pacific) - Corporate
- Canada - Home Office
- EMEA(Middle East)
- EU (European Union)
- LATAM (Latin America)
- US (United States)

### `Customer Segments`
- 
- 
- 

Based on these, there are 21 unique "Market-Segments" for which the sales forecasts can be made. That is the dataset needs to be prepared such that we get the Order-Date, Sales and Profit for the 21 market segments.<br><br>

Now, due to certain unpredictable circumstances in the market, as a company, we are prioritizing only the best and most consistent market segment in terms of profitability. We want to see which market segment is the most consistently profitable. And then, we want to forecast the sales for that most consistently profitable market-segment only. 

This way we know that the market region the company is investing in will be beneficial for the company as the forecasts will be reliable. As of now, we do not want to focus on other market segments that might have not been very consistent and profitable to the company.