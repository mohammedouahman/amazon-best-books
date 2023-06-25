# Amazon Books Scraper

## Overview
This Jupyter Notebook contains code for scraping information about the best-selling books on Amazon. It retrieves data such as book names, authors, ratings, number of customers who rated the book, and prices. The scraped data is stored in a CSV file named `amazon_products.csv`.

## Prerequisites
Before running the notebook, ensure that you have the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- re
- time
- datetime
- matplotlib.dates
- matplotlib.ticker
- urllib
- BeautifulSoup
- requests

You can install these libraries by running the following command:

```
pip install pandas numpy matplotlib seaborn re time datetime urllib BeautifulSoup requests
```

## Usage
1. Open the Jupyter Notebook `Amazon_Books_Scraper.ipynb`.
2. Ensure that you have the necessary libraries installed.
3. Execute the code cells in the notebook by pressing Shift+Enter or by clicking the "Run" button.
4. The code will scrape the information from the Amazon website and save it in the `amazon_products.csv` file.
5. The shape of the DataFrame will be displayed as the output.

## Customization
- You can modify the `no_pages` variable to specify the number of pages to scrape. By default, it is set to 2, but you can increase or decrease it as per your requirements.
- The scraped data includes book names, authors, ratings, number of customers who rated the book, and prices. If you need additional information, you can modify the code accordingly.

## Output
The scraped data is saved in a CSV file named `amazon_products.csv`. You can find this file in the same directory as the Jupyter Notebook.

## Note
This code is intended for educational purposes only. Please be respectful of website scraping policies and use this code responsibly.
