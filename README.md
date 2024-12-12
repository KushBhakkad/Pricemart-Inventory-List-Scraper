# Pricemart-Inventory-List-Scraper

## Project Overview
This project automates the process of scraping inventory data from an e-commerce website using Selenium and BeautifulSoup. The script captures details from product cards across multiple pages of a shopping website’s category, simulating human behavior to avoid detection.

## Features
- **Inventory Extraction:** Collects product details from a shopping website.
- **Human-like Interaction:** Mimics human behavior to bypass anti-bot mechanisms.
- **Logging:** Provides detailed logs for debugging and monitoring scraping progress.
- **Scalable Design:** Handles multiple pages dynamically.

## Technologies Used
- **Programming Language:** Python
- **Tools and Libraries:**
  - Selenium for browser automation
  - BeautifulSoup for parsing HTML content
  - ChromeDriver for controlling Chrome browser
  - Standard Python libraries like `random`, `time`, and `logging` for delays, randomness, and logging

## Installation
### Prerequisites
- Python 3.8 or higher
- Chrome browser installed
- ChromeDriver installed and accessible

## Usage
1. Run the script:
   ```bash
   python inventory_list_scraper.ipynb
   ```
2. Follow these steps during execution:
   - Monitor the logs to track progress.
   - View the output of scraped data in the console.

## Key Files
- `inventory_list_scraper.ipynb`: Main script for scraping inventory data.
- `scraper.log`: Log file containing detailed scraping activities and errors.

## Example Output
The script logs all captured inventory data, such as:
```
Page 1: Found 20 result cards
Result Card: Product Name: Example Product, Price: $10.99, Availability: In Stock
```

## Future Enhancements
- **Data Export:** Save the extracted data to a CSV or database for analysis.
- **Advanced Parsing:** Extract more specific details like product images and descriptions.
- **Rate Limiting:** Add smarter rate-limiting mechanisms to avoid detection.
