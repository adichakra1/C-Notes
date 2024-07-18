# Web Scraping Projects

## Premier League Web Scraper 
#### Football_matches_data_scraping.ipynb
This project is a Python-based web scraper designed to collect detailed football statistics from the FBRef website for Premier League teams. It focuses on gathering data such as match scores, fixtures, and shooting statistics, providing a comprehensive dataset for further analysis and insights into team performance across different seasons.

Project Overview
The primary goal of this project is to automate the collection of football data from a reliable online source and structure it in a format suitable for analysis. By leveraging Python's web scraping libraries, the project extracts data from various pages on FBRef, cleans and merges it, and finally compiles it into a Pandas DataFrame. This dataset can then be used for various analytical tasks, such as performance analysis, trend identification, and predictive modeling.

Features
Automated Data Collection: The script automates the process of visiting multiple web pages to gather relevant data, reducing the need for manual data entry.
Data Parsing and Extraction: Utilizes BeautifulSoup for parsing HTML content and extracting specific elements such as tables, links, and text.
Data Merging: Combines data from different sections (e.g., match scores and shooting statistics) into a unified dataset.
Support for Multiple Seasons: Iterates through different seasons to collect historical data, providing a comprehensive dataset for longitudinal analysis.
Rate Limiting: Includes delays between requests to prevent overwhelming the target server, ensuring responsible web scraping practices.

Requirements:
- Python 3.x
- Required Libraries:
- requests
- beautifulsoup4
- pandas
