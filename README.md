# Book Data Web Scraping Project

## Overview
This project scrapes book information from [BooksToScrape.com](http://books.toscrape.com) using Python.  
It extracts book title, price, rating, availability, and product page links, then exports all **1,000 books** to CSV, with a cleaned Excel version for analysis.

## Features
- Scrapes multiple pages with pagination
- Extracts the following fields:
  - Title
  - Price
  - Rating
  - Availability
  - Product Page URL
- CSV output plus a cleaned Excel file
- Polite scraping using delays to avoid server overload

## Tools & Skills
- Python
- Requests
- BeautifulSoup
- pandas / Excel export
- Data extraction

## Files
- `book_scraper.py` – Python script for scraping
- `books_clean.xlsx` – Cleaned data (1,000 books)
- `Book_Scraping_Portfolio.pdf` – Portfolio PDF with screenshots and process explanation

## How to Use
1. Clone this repository:  
   `git clone https://github.com/Tadrous-William/book-scraping-project.git`
2. Install dependencies:  
   `pip install requests beautifulsoup4`
3. Run the scraper:  
   `python book_scraper.py`
4. The data is saved to `books.csv`
