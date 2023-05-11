
# BigBasket Web Scraper

This project demonstrates a web scraper for the online grocery store BigBasket. The scraper extracts product information from multiple categories and subcategories, and saves the data in an Excel file. Additionally, it can upload the data to a new Google Sheets document.




## Features

- Scrapes product information from multiple categories and   subcategories
- Saves the data to an Excel file
- Uploads the data to a new Google Sheets document
- Customizable time intervals for data saving
- Headless scraping using Selenium
## Requirements

- Python 3.6 or higher
- Chrome WebDriver

The following Python libraries:

- pandas
- openpyxl
- selenium
- BeautifulSoup
- google-auth
- google-api-python-client
## Installation

1. Clone the repository:

```bash
git clone https://github.com/username/bigbasket-scraper.git
cd bigbasket-scraper
```

2. Install the required Python packages:

```bash
pip install -r requirements.txt
```


## Usage

1. Open bigbasket_scraper.py in your favorite code editor, and update the my_email variable with your email address.

2. Download a credentials.json file for your Google Cloud project, and place it in the project directory (https://developers.google.com/workspace/guides/create-credentials).

3. Run the cells of bigbasket_scraper.ipynb notebook.

4. The script will scrape the product information from BigBasket and save it to an Excel file named bigbasket_data.xlsx.

5. After the scraping process is complete, the script will upload the data to a new Google Sheets document and provide you with the URL.
## License

This project is licensed under the MIT License. 
