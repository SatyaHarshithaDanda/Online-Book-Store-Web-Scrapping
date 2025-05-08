# 📚 Online Book Store Web Scraping

This project showcases how to scrape data from an **online book store website** using Python. The goal is to collect information such as book titles, prices, ratings, and availability to analyze trends and enable data-driven insights for users or businesses.

## 🎯 Objective

- Scrape structured data from an online book store website (e.g., [books.toscrape.com](http://books.toscrape.com/)).
- Extract book details like title, price, stock status, and star rating.
- Store and clean the data using Pandas.
- Optionally analyze the data to gain insights on pricing, genre popularity, or availability.

## 🧰 Tools & Technologies Used

- **Python**
- **Requests** – To fetch web pages
- **BeautifulSoup** – To parse and extract HTML data
- **Pandas** – For structuring and analyzing data
- **Jupyter Notebook** – For running and documenting the scraping process

## 🕸️ Target Website

- The scraping is performed on a mock e-commerce website for books, typically:  
  [http://books.toscrape.com](http://books.toscrape.com)

## 🗂️ Data Extracted

Each book entry includes:
- 📖 **Title**
- 💰 **Price**
- 🌟 **Rating** (e.g., One to Five stars)
- 📦 **Availability** (In stock or out of stock)
- 🔗 **Product URL** (optional)

## 🔍 Key Features

- Iterative scraping through multiple pages
- Parsing star ratings using class attributes
- Handling inconsistent data formats and tags
- Storing data in CSV format for further analysis

## 📊 Potential Insights

- Price range and distribution of books
- Most frequent rating among available books
- Availability trends
- High vs. low-rated book pricing patterns

## 🧠 Skills Demonstrated

- Web Scraping & HTML Parsing
- Data Cleaning & Transformation
- Data Storage in Structured Formats
- Automation of Data Collection

## ▶️ How to Run

1. Clone this repository or download the `.ipynb` file.
2. Install required Python libraries:
   ```bash
   pip install requests beautifulsoup4 pandas
3. un Online_Book_Store_Web_Scrapping.ipynb in Jupyter Notebook.
4. The extracted data will be saved as a .csv file for further use.

## ⚠️ Disclaimer

This project is intended for educational purposes only. Always respect website terms of service before scraping.
