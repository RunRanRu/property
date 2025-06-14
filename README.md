# Property Listings Scraper (Malaysia)

## Overview
Scrapes property listings from [PropertyGuru](https://www.propertyguru.com.my/) and [iProperty](https://www.iproperty.com.my/) Malaysia, extracting:
- Images
- Project name
- Price
- Price per square feet
- Description
- Tenure (Freehold/Leasehold)
- Amenities

## Usage

1. **Install dependencies:**
   ```
   pip install -r requirements.txt
   ```

2. **Run the scraper:**
   ```
   python main.py
   ```

3. **Output:**  
   Listings saved to `data/listings.csv`

## Customizing
- Update CSS selectors in `scrapers/propertyguru.py` and `scrapers/iproperty.py` as needed (inspect site HTML).
- Adjust URLs or add filters as needed.

## Notes
- Respect robots.txt and site terms of service.
- For JavaScript-heavy pages, use Selenium or Playwright instead.
- Rate-limit your requests to avoid blocking.
# property
