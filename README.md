# web-scraping-romanian-companies
A Python web scraping project that extracts data from the "List of companies of Romania" Wikipedia page using BeautifulSoup and requests. The extracted information is then organized into a Pandas DataFrame and saved as a CSV file. This project serves as a practical example of web scraping techniques for data extraction and manipulation.

# Web Scraping Project

## Overview
This Python script scrapes data from the Wikipedia page "List of companies of Romania" - https://en.wikipedia.org/wiki/List_of_companies_of_Romania using BeautifulSoup and requests. The extracted data is then converted into a Pandas DataFrame and saved as a CSV file.

## Tools Used
- Python
- BeautifulSoup
- Requests
- Pandas

## Getting Started
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/web-scraping-project.git


## Implementation
1. Web Scraping:

    The program sends a GET request to the Wikipedia page using the requests library.
    The HTML content of the page is then parsed using BeautifulSoup, creating a structured representation of the HTML.

2. Extracting Table Headers:

    The script locates the first table on the page and extracts the headers (column names) from the table's header cells (<th>).


3. Extracting Table Data:
   
    The program then extracts the data from the table rows (<tr>) and cells (<td>).
    The extracted data is stored in a Pandas DataFrame.
   
4. Saving Data to CSV:
   
   Finally, the DataFrame is saved as a CSV file with tab-separated values to maintain proper formatting.

   
   ![python_script_tabel](https://github.com/PopoviciGeorgeOctavian/web-scraping-romanian-companies/assets/116513072/0c1f5a5f-f1d0-44ef-84e9-57c44c98419d)
