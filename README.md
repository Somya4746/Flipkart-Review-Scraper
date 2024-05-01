
# Flipkart Review Scraper

## Overview
Flipkart Review Scraper is a web application built with Flask, designed to scrape and display product reviews from Flipkart. This tool is invaluable for anyone looking to analyze consumer feedback on products listed on Flipkart without manually browsing through each product page.

## Features
- **Scrape Reviews:** Automatically fetches reviews for any product available on Flipkart.
- **User Interface:** Simple and intuitive web interface to enter product names and view results.
- **Data Extraction:** Leverages BeautifulSoup and Requests to efficiently parse and extract data.
- **Error Handling:** Robust error management to handle and log exceptions and issues during the scraping process.
- **Data Storage:** Reviews are saved in CSV format, making them easy to export and analyze.

## Technologies Used
- **Flask:** For setting up the web server and handling HTTP requests.
- **BeautifulSoup:** Used for parsing HTML and extracting the needed data.
- **Requests:** For making HTTP requests to Flipkart's web pages.
- **Python Logging:** For logging information, warnings, and errors.
- **Flask-CORS:** Handles cross-origin requests to the Flask server.

## Installation

To get this project up and running on your local machine, follow these steps:

1. **Clone the repository**
   ```bash
   git clone https://github.com/Somya4746/Flipkart-Review-Scraper.git
   ```
2. **Navigate to the project directory**
   ```bash
   cd Flipkart-Review-Scraper
   ```
3. **Install required Python packages**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

After installing, you can run the server using:

```bash
python app.py
```

Open a web browser and go to `http://127.0.0.1:5000/` to access the application. Enter the product name you want to scrape reviews for, and the results will be displayed on the web page.

