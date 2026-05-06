# 🌐 Web Scraping — Fortune 500 US Companies by Revenue

## Project Overview
This project demonstrates an end-to-end web scraping pipeline built 
in Python. Data was extracted from a live Wikipedia page listing the 
Fortune 500 largest US companies by revenue, then cleaned and 
structured for analysis using Pandas.

## Objectives
- Automate data collection from a live web source
- Parse HTML structure using BeautifulSoup to isolate target tables
- Clean and structure raw extracted data into an analysis-ready format

## Tools & Technologies
- Python 3
- Requests — HTTP requests to fetch live web page
- BeautifulSoup — HTML parsing and table extraction
- Pandas — data structuring, cleaning, and formatting
- Jupyter Notebook — documented workflow

## Key Steps
1. Sent HTTP request to Wikipedia page using Requests library
2. Parsed full HTML response using BeautifulSoup
3. Located and extracted the Fortune 500 revenue table from raw HTML
4. Loaded extracted data into a Pandas DataFrame
5. Applied column formatting, data typing, and cleaning
6. Produced a structured, query-ready dataset

## Skills Demonstrated
- Web scraping and automated data collection
- HTML structure navigation and parsing
- Data cleaning and transformation with Pandas
- Reproducible, documented analytical workflow

## Data Source
Wikipedia — List of Largest Companies in the United States by Revenue
https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue

