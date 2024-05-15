**Project Setup And Guidelines**

## Overview

This Amazon Product Scraper is a tool designed to extract product information from various categories on Amazon.com. It scrapes product data including name, price, description, colors, up to 5000 reviews (This Code Can Potentially Scrap Thousands Of Iterations Of Products) and other relevant details, and stores it in JSON format for further analysis or use.

## Features

- Scrapes products from multiple categories.
- Navigates through subcategories and sub-subcategories.
- Stores scraped data in JSON format.
- Easy to use and customize.

## Dependencies
- Download the Chrome WebDriver compatible with your Chrome browser version from Chrome WebDriver Downloads and ensure it's in your system's PATH.
- Install Selenium
- Install BeautifulSoup

## Dependencies
- Python 3
- Selenium
- BeautifulSoup
- Any IDE of your choosing

## Script Description

Imports necessary libraries beforehand.

Configures Chrome options and initializes the WebDriver.

Navigate to Amazon's main page and select Men's Fashion category.

Iterates through product pages, scraping product information, including URLs, titles, categories, genders, descriptions, image URLs, prices, and reviews.
Stores the collected data in a JSON file.

## Sample Output:
Scraped data includes product URLs, titles, categories, genders, descriptions, image URLs, prices, and reviews.

Adjustments may be needed for XPath selectors or sleep times based on Amazon's site changes or network conditions.
Ensure compliance with Amazon's terms of service and robots.txt when scraping data from their website.
Pagination support is implemented to scrape multiple pages of products.
