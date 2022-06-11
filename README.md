# Scraping-Stock-Prices-on-Yahoo-Finance
Scraping the top tickers for each market category on the Yahoo Finance website and generating a CSV for each market type with ticker information.

This is my first python project ever and I would like to thank my bootcamp for having me execute it. It made me realize the power of a programming language in almost browsing the web for me and getting me the information I needed in a concise format, all in little over 2 seconds!  

In the project, five different functions were written. The functions are as follows:  
- get_market_page: This function would create a beautifulsoup document for each of the market categories on the Yahoo Finance website. 
- parse_ticker: This function checks the html code for specific tags and collects various aspects of information about each ticker. 
- get_top_tickers: This function takes a particular market type as input and parses the tickers for the market mentioned. 
- write_csv: This function takes each of the markets as input and places the information of each ticker in a row, as well as provide headings. The resulting file is saved in a csv which can be accessed for future use. 
- scrape_market_tickers: This function can be passed into a for loop with several market types as inputs, and spits out csvs with ticker info for each market. 
 
The Beautifulsoup package provides an excellent pathway to scrape websites. However, it cannot be used easily for dynamic websites. I would love to try out Selenium for scraping dynamic websites in a future project.
