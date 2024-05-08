**Project Setup And Guidelines**
## Dependencies
- Download the Chrome WebDriver compatible with your Chrome browser version from Chrome WebDriver Downloads and ensure it's in your system's PATH.
- Install Selenium
- Install BeautifulSoup

## Dependencies
- Python 3
- Selenium
- BeautifulSoup

## Script Description

Imports necessary libraries.

Configures Chrome options and initializes the WebDriver.

Navigate to Amazon's main page and select Men's Fashion category.

Iterates through product pages, scraping product information, including URLs, titles, categories, genders, descriptions, image URLs, prices, and reviews.
Stores the collected data in a JSON file.

## Sample Output:
Scraped data includes product URLs, titles, categories, genders, descriptions, image URLs, prices, and reviews.
Notes

Adjustments may be needed for XPath selectors or sleep times based on Amazon's site changes or network conditions.
Ensure compliance with Amazon's terms of service and robots.txt when scraping data from their website.
Pagination support is implemented to scrape multiple pages of products.
