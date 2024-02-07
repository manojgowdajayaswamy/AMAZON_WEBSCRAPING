# Amazon Web Scraping

This repository contains a Python script for web scraping Amazon product data, focusing on extracting product titles and ratings. The script utilizes the `requests` library for making HTTP requests and `BeautifulSoup` for parsing HTML content.

## Prerequisites
- Python 3.x
- `requests` library
- `BeautifulSoup` library
- `pandas` library (optional for data analysis)

## Instructions
1. Clone this repository to your local machine.
2. Ensure that you have the required libraries installed (`requests`, `BeautifulSoup`, `pandas`).
3. Modify the `URL` variable in the script to specify the Amazon product page URL you want to scrape.
4. Run the script using Python.

## Script Overview
- The script retrieves the HTML content of the specified Amazon product page.
- It extracts the product title and average customer rating from the HTML content.
- The data is then stored in a CSV file named `webscrapingamzdata.csv` along with the current date.
- The script is designed to continuously check and update the ratings in real-time, with a 5-second interval.
- The CSV file can be used for further analysis, such as visualizations or data manipulation using libraries like `pandas`.

## Notes
- Ensure compliance with Amazon's terms of service when scraping their website.
- Consider adding appropriate error handling and exception catching to enhance the robustness of the script.
