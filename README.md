Project Ideas:
- Stock Screener (core) - NEXT ON THE LIST.
- How many publicly listed securities are there in the world and where? - FINISHED ("GlobalVisualExchange.ipnyb" utilized all_stock_exchanges_complete.json and stock_exchanges_coordinates.json)
- Chart with Trading Signals based on Bollinger Bands. - THIRD ONE ON THE LIST BUT MAY INTERTWINE WITH STOCK SCREENER - LINDA RASHKE.


Review of:
- Pandas
- API
- FRED API
- Surveys and RCTs -> Which market globally is performing better, industry, security within.
- Visualization
- Mapping onto visualiation library
- (SQL)?


When we scrape using yfinance API, the output does not have the ticker name in the columns so we must clean the data by adding a ticker column for each query. 
Source: https://stackoverflow.com/questions/63107594/how-to-deal-with-multi-level-column-names-downloaded-with-yfinance/63107801#63107801


- stack function
- merge function
- 
Essence of the Project:
What are we trying to do with this project?
Query for ALL publicly listed securities, grab their market capitalization number (equity for shareholders) 
Get a single-level column of 
Identify where they are from.
Input mapping coordinates to each security's exchange.
Plot using 3-d mapping visualization widgets.

What do we have?
- List of all [stock exchange, longitude, latitude]
- 


Process
1) Import all required libraries and APIs, per documentation, stackoverflow, other advice
2) Rate limiter so we can query ALL publicly listed securities
3) Figure out how to query for ALL securities
4) Clean data so it's usable.
5) 
