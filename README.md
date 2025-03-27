 Final Assignment – Tesla & GameStop Stock & Revenue Analysis

This project is part of the final assignment for the Python for Data Science course. It involves extracting stock and revenue data for Tesla and GameStop, cleaning the data, and visualizing trends using Python.

 Project Overview

The notebook performs the following tasks:

1. Stock Data Extraction
   - Uses the `yfinance` library to extract historical stock data for:
     - Tesla (Ticker: TSLA)
     - GameStop (Ticker: GME)

2. Revenue Data Extraction via Web Scraping
   - Uses the `requests` and `BeautifulSoup` libraries to scrape revenue data from HTML pages.
   - Revenue data is parsed and cleaned, removing symbols like `$` and `,`.

3. Data Cleaning
   - Converts revenue data from strings to floats.
   - Drops rows with missing or invalid data.

4. Data Visualization
   - Uses a provided `make_graph()` function to plot stock prices alongside revenue over time.
   - Graphs show trends up to June 2021.

 Technologies Used

- Python 3
- Jupyter Notebook
- `yfinance` for financial data
- `pandas` for data manipulation
- `requests` and `BeautifulSoup` for web scraping
- `matplotlib` for visualization (through `make_graph()` function)

 Outputs

- Cleaned DataFrames for Tesla and GameStop stock and revenue.
- Stock vs. Revenue line plots for both companies.

 Files

- `Final Assignment (3).ipynb`: Main Jupyter notebook.
- `README.md`: This file.

 Learning Objectives

- Practice data extraction using APIs and web scraping.
- Apply data cleaning techniques.
- Visualize data relationships using graphs.
- Combine stock market data with financial performance metrics.

---

Let me know if you'd like a version of this README tailored for GitHub formatting, or if you want to include screenshots or outputs!
