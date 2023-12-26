# Flight Scraper: Helsinki to Various Destinations

## Project Overview
This project includes a Colab notebook with functions designed to scrape flight data for trips from Helsinki to various destinations. It utilizes Selenium and the Chrome Webdriver to fetch data from multiple travel sites.

## Features
- Scraping flight data from multiple sources: Booking.com, Kayak, and Momondo.
- Comprehensive analysis of flight data, with detailed explanations in the notebook.

## Getting Started

### Prerequisites
- Google Chrome Browser
- Chrome Webdriver (compatible with your Chrome version)
- Selenium and Selenium-Stealth for Python

### Installation
Run the following commands in your Colab notebook to set up the environment:

```bash
!apt install chromium-chromedriver
!pip install selenium
!pip install selenium-stealth
!wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb && apt install ./google-chrome-stable_current_amd64.deb
```


### Note
If you encounter issues with the Chrome Webdriver, please refer to the Selenium documentation for updates on the driver and specific versions of Selenium Stealth compatible with your system
