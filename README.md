# CodeAlpha_Web-Scraping
### 🎯 Objective

Extract book details — *title, price, availability, and rating* — from the website and store them in a structured CSV dataset.

## 🧩 *Short Report 
*Website Scraped:* [Books to Scrape](https://books.toscrape.com)
*Libraries Used:* requests, BeautifulSoup, pandas

*Data Fields Collected:*
* Title of the book
* Price
* Availability status
* Star rating

*Process Summary:*
The Python script fetches HTML content from multiple pages using the requests library, then parses it with BeautifulSoup to extract specific tags and attributes. The extracted data is stored in a list of dictionaries, converted to a Pandas DataFrame, and exported to a CSV file.

*Challenges:*

* Understanding HTML structure (classes and tags)
* Handling multiple pages using a loop
* Extracting the star rating embedded in CSS class names

*Output:*
A clean dataset (books_dataset.csv) ready for further analysis or visualization.
