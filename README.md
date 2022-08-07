# NY-Times-vs-Stocks
We will use the NY Times API and the MarketStack API's free tier to check for correlation between articles and movement in the stock market.

Here is a breakdown of the endpoints for Market Stack API according to their quickstart documentation, which can be found at: https://marketstack.com/quickstart.


// End-of-Day Data API Endpoint

http://api.marketstack.com/v1/eod
    ? access_key = YOUR_ACCESS_KEY
    & symbols = AAPL
    
// optional parameters: 

    & sort = DESC
    & date_from = YYYY-MM-DD
    & date_to = YYYY-MM-DD
    & limit = 100
    & offset = 0



// Intraday Data API Endpoint

http://api.marketstack.com/v1/intraday
    ? access_key = YOUR_ACCESS_KEY
    & symbols = AAPL
    
// optional parameters: 

    & interval = 1h
    & sort = DESC
    & date_from = YYYY-MM-DD
    & date_to = YYYY-MM-DD
    & limit = 100
    & offset = 0


// Tickers API Endpoint

http://api.marketstack.com/v1/tickers
    ? access_key = YOUR_ACCESS_KEY
    
// optional parameters: 

    & exchange = 
    & limit = 100
    & offset = 0



// Exchanges API Endpoint

http://api.marketstack.com/v1/exchanges
    ? access_key = YOUR_ACCESS_KEY
    
// optional parameters: 

    & limit = 100
    & offset = 0



// Currencies API Endpoint

http://api.marketstack.com/v1/currencies
    ? access_key = YOUR_ACCESS_KEY
    
// optional parameters: 

    & limit = 100
    & offset = 0


// Timezones API Endpoint

http://api.marketstack.com/v1/timezones
    ? access_key = YOUR_ACCESS_KEY
    
// optional parameters: 

    & limit = 100
    & offset = 0