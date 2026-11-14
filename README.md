FlyRank A9 – Polite Web Scraper

A Python-based web scraping project that extracts, cleans, normalizes, and validates book information from Books to Scrape.

Project Overview

This project demonstrates an automated web scraping pipeline designed to collect structured book information while handling request failures, caching responses, and validating extracted records.

The scraper collects book data from catalogue pages and processes it into clean JSON output.

Features

* Web Scraping: Fetches website content using Python Requests.
* HTML Parsing: Uses BeautifulSoup to extract book information.
* Data Extraction: Collects book titles, prices, availability, ratings, descriptions, and product URLs.
* Data Normalization: Converts extracted information into a consistent structure.
* Data Validation: Validates records and separates invalid data.
* Caching: Stores fetched HTML responses to reduce repeated requests.
* Error Handling: Handles failed HTTP requests and skips unsuccessful pages.
* JSON Export: Saves structured records and execution reports in JSON format.

Technologies Used

* Python
* Requests
* BeautifulSoup4
* Pydantic
* JSON
* Google Colab
* GitHub

Project Workflow

1. Install the required Python libraries.
2. Fetch catalogue pages from Books to Scrape.
3. Extract individual book URLs.
4. Fetch book details.
5. Parse and normalize the extracted information.
6. Validate the records.
7. Handle failed requests and invalid records.
8. Export the final results into JSON files.

Project Results

Metric	Result
Catalogue pages	3
Books discovered	60
Unique URLs	60
Successful records	60
Valid records	60
Invalid records	0
Failed pages	1

Output Files

* books.json – Clean and validated book records.
* errors.json – Error and validation information.
* run-report.json – Scraping execution summary.
* raw_books.json – Raw extracted records.

How to Run

1. Open the Jupyter Notebook in Google Colab.
2. Install the required dependencies.
3. Execute the notebook cells in sequence.
4. View the generated JSON files in the output directory.

Learning Outcomes

Through this project, I gained practical experience in:

* Python-based web scraping.
* HTML parsing and data extraction.
* Data cleaning and validation.
* HTTP requests and error handling.
* Caching and efficient data collection.
* Structuring and exporting JSON datasets.

Data Source

Books to Scrape

This project was developed for educational and portfolio purposes.

Author

Charvi Jain

GitHub: charvie-web