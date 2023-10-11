# Data-Curation-and-Analysis-Project

### Project Goal
The goal of this project is to construct, analyze, and publish a dataset about US stock symbols to data.world. This repository contains all the data, the documentation and the single Jupyter notebook file where all data analysis techniques were performed to create the dataset.

### API Links
BeautifulSoup: https://beautiful-soup-4.readthedocs.io/en/latest/#. Pandas: https://pandas.pydata.org/docs/. Requests: https://docs.python-requests.org/en/latest/user/quickstart/. Matplotlib: https://matplotlib.org/stable/index.html.

### MIT License
Copyright (c) 2023 [Abhiram Naredla]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

### Data Dictionary
Symbol - Ticker symbol to identify stock.

Company Name - Name of the company.

Industry - Industry of the company.

Market Cap - Total value of company shares.

### Special Characteristics of Data
The dataset only uses the first 500 entries out of the 5792 total US stocks. Moreover, market cap data is given in a mix of billions of dollars and millions of dollars. For instance, the market cap of "Apple Inc." is 2,788.98B and for "WK Kellogg Co" is 922.72M.
