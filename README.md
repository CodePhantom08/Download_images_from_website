# Download_images_from_website

This is a simple Flask web application that allows users to enter a URL, scrape images from the webpage using Selenium and BeautifulSoup, and download them as a ZIP file.

## Features
- Scrapes all images from a given webpage.
- Downloads images into a local folder.
- Provides a ZIP file containing all the images for easy download.
- Runs in headless mode using Selenium.

## Prerequisites
Before running this application, ensure you have the following installed:
- Python 3.x
- Google Chrome
- ChromeDriver (managed automatically by `webdriver_manager`)

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/Download_images_from_website.git
   cd Download_images_from_website
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the Flask application:
   ```bash
   python app.py
   ```

2. Open a web browser and go to:
   ```
   http://127.0.0.1:5000/
   ```

3. Enter a URL, click submit, and download the scraped images as a ZIP file.

## Dependencies
- Flask
- Selenium
- Webdriver Manager
- Requests
- BeautifulSoup
- Zipfile


