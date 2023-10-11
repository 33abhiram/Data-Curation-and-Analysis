# Data-Curation-and-Analysis-Project

### Project Goal
The goal of this project is to construct, analyze, and publish a dataset about US stock symbols to data.world. This repository contains all the data, the documentation and the single Jupyter notebook file where all data analysis techniques were performed to create the dataset.

To gather data, I used python's BeautifulSoup web-scraping library. Its documentation can be found here: https://beautiful-soup-4.readthedocs.io/en/latest/#.

### Data Dictionary
Symbol - Ticker symbol to identify stock.

Company Name - Name of the company.

Industry - Industry of the company.

Market Cap - Total value of company shares.

### Special Characteristics of Data
The dataset only uses the first 500 entries out of the 5792 total US stocks. Moreover, market cap data is given in a mix of billions of dollars and millions of dollars. For instance, the market cap of "Apple Inc." is 2,788.98B and for "WK Kellogg Co" is 922.72M.
