# S&P500 Stock Price Market News Search Engine

We build a sample information retrieval system with big data obtained from REST API service using Python requests library for News data. For historical stock price data, we extract stock-related data for S&P 500 companies from Yahoo Finance using finance package.

- We use Elasticsearch, because we are more interested in searches, thus Elasticsearch is more appropriate.
- Furthermore, when dealing with historical stock price data, our data is represented as CSV files, so we use SQL database, since it is table-based data, structured data type.
- We use PostgreSQL, which it is suitable to store and search time series data.
- We also use Spark to search the results.
- Last but not least, we use Flask which is a web development framework developed in Python. It is easy to use and show our result.


<img align="center" src="https://github.com/yyyukeqi/S-P500-Stock-Price-Market-News-Search-Engine/blob/main/images/ETL%20pipeline.png" width="1200" height="768" />
