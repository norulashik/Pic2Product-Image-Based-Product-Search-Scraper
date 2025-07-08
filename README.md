# Pic2Product-Image-Based-Product-Search-Scraper
A Python-based tool that takes an input image, identifies the product, and fetches online shopping links, prices, reviews, and descriptions from e-commerce sites. The results are stored in a CSV for easy reference.
## Features

- Upload an image (JPEG/PNG).
- Detect product identity using OCR, image captioning, and search keywords.
- Search and extract online buying links using DuckDuckGo and SerpAPI.
- Scrape product metadata including:
  - Price
  - Description
  - Ratings
  - Reviews
- Export structured data to a CSV file.


## Technologies Used

- Python
- OpenCV
- Tesseract OCR
- Google Search / DuckDuckGo API (via SerpAPI)
- BeautifulSoup for scraping
- Pandas for data handling
- Jupyter Notebook interface
