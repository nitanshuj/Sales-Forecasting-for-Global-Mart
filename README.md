# Sales Forecasting for Global Mart

### Tech Stack
Programming Languages: Python <br>
ML and Forecasting: Time Series Forecasting (Smoothing and Autoregressive Methods), Data Analysis

## Business Understanding
Global Mart is an online supergiant store that has worldwide operations. 

This store takes orders and delivers across the globe and deals with all the major product categories — consumer, corporate and home office.
As a sales manager for this store, we have to forecast the sales of the products for the next 6 months, so that we have a proper estimate and can plan wer inventory and business processes accordingly.


## Variables
The data consists of 7 different geographical market segments and 3 major customer segments.

### `Markets`
- Africa
- APAC (Asia Pacific)
- Canada
- EMEA (Middle East)
- EU (European Union)
- LATAM (Latin America)
- US (United States)

### `Customer Segments`
- Consumer
- Corporate
- Home Office

Based on these, there are 21 unique "Market- CUstomer Segments" for which the sales forecasts can be made. That is the dataset needs to be prepared such that we get the Order-Date, Sales and Profit for the 21 market segments.

The 21 market-segments (combinations) are:

- 'US-Consumer', 'US-Corporate', 'US-Home Office'
- 'APAC-Corporate', 'APAC-Consumer', 'APAC-Home Office'
- 'EU-Home Office','EU-Corporate', 'EU-Consumer'
- 'EMEA-Corporate', 'EMEA-Consumer', 'EMEA-Home Office'
- 'Africa-Consumer', 'Africa-Corporate', 'Africa-Home Office'
- 'LATAM-Home Office', 'LATAM-Consumer', 'LATAM-Corporate'
- 'Canada-Corporate', 'Canada-Home Office', 'Canada-Consumer'

Now, due to certain unpredictable circumstances in the market, as a company, we are prioritizing only the best and most consistent market segment in terms of profitability. We want to see which market segment is the most consistently profitable. And then, we want to forecast the sales for that most consistently profitable market-segment only. 

This way we know that the market region the company is investing in will be beneficial for the company as the forecasts will be reliable. As of now, we do not want to focus on other market segments that might have not been very consistent and profitable to the company.

So, not all of these 21 market segments are important from the store’s point of view. You need to find out the most consistently profitable market-segment from the above and forecast the sales and demand for that single market-segment only and not for all.



## Goal and Objectives
How do you find that most profitable market segment from the 21 market segments?


