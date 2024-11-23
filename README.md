SeleniumScraper: Automated Price Tracking and Data Logging
This project automates price tracking and logs data from product pages on e-commerce websites using Selenium WebDriver. It scrapes product prices, stores them in a CSV file, and allows you to set a price threshold for price alerts.

Features
Scrapes product price, name, and the date from an e-commerce website (example: Myntra).
Tracks the price and logs it in a CSV file.
Sends alerts when the product price falls below a set threshold.
Runs in headless mode to avoid opening a browser window.
Uses a dynamic user-agent to mimic real user behavior and avoid detection.
Technologies Used
Python: The main programming language.
Selenium: Web scraping and browser automation.
Fake User-Agent: To rotate user-agents for mimicking real user traffic.
CSV: For storing product data.
Chrome WebDriver: For interacting with the Chrome browser.
Requirements
To run this project, you will need to install the dependencies listed in requirements.txt. You can install them with the following command:
pip install -r requirements.txt

Dependencies in requirements.txt:
selenium
fake_useragen