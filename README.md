Project Repository README
Overview
This repository contains a collection of Python scripts and programs demonstrating various data handling, analysis, and visualization techniques. The projects span web scraping, financial data extraction, music library management, GDP data processing, customer data filtering, sales data analysis, and basic calculations. These scripts are designed to support learning and practical application in data science, business intelligence (BI), and financial analysis.
Contents

Extracting Stock Data Using a Web Scraping

File: Extracting Stock Data Using a Web Scraping.txt
Description: Demonstrates web scraping to extract stock data (e.g., Netflix) using requests and BeautifulSoup. The script creates a pandas DataFrame with stock metrics (Date, Open, High, Low, Close, Volume) and compares it with data loaded via pd.read_html.
Dependencies: pandas, requests, bs4, html5lib, lxml, plotly
Usage: Run to fetch and display Netflix stock data from a specified URL.


Music Library

File: music_library.txt
Description: A program to manage and analyze a music album collection. It includes functions for calculating scores, genre frequency, album ratings, and printing high-rated albums using loops, dictionaries, and variable scope.
Features:
calculate_score: Computes a score based on rating and bonus.
get_genre_frequency: Counts genre occurrences.
rate_album: Rates albums based on a favorite band.
print_high_rated_albums: Displays albums above a rating threshold.
print_album_info: Shows album details.
freq: Counts word frequency in lyrics.


Usage: Execute main() to see the functionality with sample album data.


Extracting Stock Market Data Using Python

File: Extracting Stock Market Data Using Python.txt
Description: Uses the yfinance library to download historical stock data (e.g., Apple) and visualizes it with matplotlib. Includes dividend data and JSON file handling.
Dependencies: yfinance, matplotlib, pandas
Usage: Run to fetch and plot Apple stock price and dividend data.


Modifying the .txt Files

File: modifying the .txt files.txt
Description: Manages membership data by generating and cleaning files (members.txt and inactive.txt). Uses random data generation and file operations to simulate membership status updates.
Functions:
genFiles: Creates initial membership files.
cleanFiles: Moves inactive members to a separate file.


Usage: Execute to generate and clean membership data, then print active and inactive members.


The GDP Scraper

File: the GDP scraper.txt
Description: Scrapes GDP data from a Wikipedia archive using pandas.read_html and processes it to list the top 10 economies. Saves results to a CSV file.
Dependencies: numpy, pandas
Usage: Run to fetch and save GDP data for the top 10 economies.


yfinance Library

File: yfinance library.txt
Description: A simple script using yfinance to download historical data for Microsoft (MSFT) stock.
Dependencies: yfinance, pandas
Usage: Execute to display Microsoft stock data.


Basic Calculator

File: basic calculator.txt
Description: A simple calculator performing addition, subtraction, multiplication, and division with error handling.
Usage: Run and input numbers and operation to calculate results.


Customer Data Filtering

File: Filtrowanie danych klientów.txt
Description: Filters customer data from a text file to identify and list adult customers (age ≥ 18). Reads data from customers.txt, processes it, and prints names of adult customers.
Usage: Ensure customers.txt is in the correct directory, then run to display adult customers.


Sales Data Analysis

File: Funkcja do analizy sprzedaży produktu.txt
Description: Analyzes sales data from text files in a specified directory. Includes functions to read sales data and calculate total quantities sold for a specific product (e.g., Apple).
Functions:
read_sales_data: Reads sales data from a text file and returns a list of dictionaries.
total_sales_2: Aggregates total quantity sold for a specified product across multiple files.


Usage: Ensure sales data files are in the data directory, then run to calculate and display total sales for a product.


Total Sales Calculation

File: Suma wyników sprzedaży.txt
Description: Calculates the total sales value from a sales.txt file by summing the sales amounts extracted from each line.
Usage: Ensure sales.txt is in the correct directory, then run to compute and display the total sales value.



Setup Instructions

Install Dependencies:

Run the !pip install commands provided in each script (e.g., pandas, requests, yfinance, etc.) in a Python environment (e.g., Jupyter Notebook or terminal).


Required Tools:

Python 3.x
Internet connection for web scraping and API calls


File Execution:

Copy each script into a .py file or run directly in a Python environment.
Ensure proper file paths (e.g., apple.json for stock data, customers.txt, sales.txt, or data directory for sales data) are accessible.



Usage

Each script can be run independently to explore its functionality.
Modify URLs, data sources, or parameters (e.g., stock symbols, GDP URLs, product names) as needed for your use case.
For visualization scripts, ensure a display environment is available (e.g., Jupyter Notebook).

Contributing
Feel free to fork this repository, enhance the scripts, or add new features. Submit pull requests with improvements or bug fixes.
License
This repository is for educational purposes only. Use the code responsibly and respect data source terms of service.
Contact
For questions or support, reach out via the platform where this content is hosted.
