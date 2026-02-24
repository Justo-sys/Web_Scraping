# 🏒 Web Scraping Project – NHL Team Statistics

## Overview
This project demonstrates web scraping using Python to extract structured data from the "Hockey Teams: Forms, Searching and Pagination" sandbox page on Scrape This Site.

The goal was to collect NHL team statistics and store them in a structured dataset for further analysis.

## Data Source
Website:
https://www.scrapethissite.com/pages/forms/

The page contains NHL team statistics including:
- Team Name
- Year
- Wins
- Losses
- OT Losses
- Win %
- Goals For (GF)
- Goals Against (GA)
- Goal Differential (+/-)

## Tools & Libraries Used
- Python
- requests
- BeautifulSoup (bs4)
- pandas

## Methodology
1. Sent an HTTP request to the target URL using `requests`.
2. Parsed the HTML content using `BeautifulSoup`.
3. Located the data table using class selectors.
4. Extracted column headers and row data.
5. Stored the extracted data into a Pandas DataFrame.
6. Exported the dataset as a CSV file (`Hockey.csv`).

## Output
The final output is a structured CSV file containing NHL team statistics.

## Key Learning Outcomes
- HTML parsing with BeautifulSoup
- Navigating and extracting table data
- Structuring scraped data using Pandas
- Exporting datasets for analysis

---
*This project was completed as part of a web scraping assignment and demonstrates foundational data collection skills.*
