# CodeAlpha_WebScraping
This project is part of my Data Analytics Internship at CodeAlpha.  
The objective of this task is to perform web scraping using Python and extract structured data from a public website.

Task Description:
Scraped data from a public website using Python.
Used BeautifulSoup library to parse HTML content.
Extracted book details such as:
1. Title
2. Price
3. Availability
Saved the extracted data into a CSV file for analysis.

Technologies Used
1. Python
2. BeautifulSoup
3. Requests
4. Pandas

Files in this Repository
1. `scrape_books.py` → Python script for web scraping
2. `books.csv` → Extracted dataset
3. `README.md` → Project documentation

How to Run the Project
1. Install required libraries
pip install requests beautifulsoup4 pandas
2. Run the Python script:
python scrape_books.py
3. The output file `books.csv` will be generated in the same folder.

Output
A CSV file containing scraped book data Title, Price, Availability.
