# Van-Listings-Web-Scraper-and-Data-Management
This repository contains a web scraping project built in Python that extracts van listings from a [website](https://www.camplify.co.nz/s?seed=8031&page=40) and manages the data using [Google Sheets](https://docs.google.com/spreadsheets/d/14spVQNxUEq1JIdPOKHZfjphkh-f2QOS5eD5eBv-5fsQ/edit?usp=sharing). The scraper utilizes Selenium for web scraping, gspread for interacting with the Google Sheets API, and other supporting technologies. It allows efficient scraping of van details such as type, description, location, hire fee per day, and number of reviews. The scraped data is then stored in a structured manner in a [Google Sheets](https://docs.google.com/spreadsheets/d/14spVQNxUEq1JIdPOKHZfjphkh-f2QOS5eD5eBv-5fsQ/edit?usp=sharing) document for easy access and analysis.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run the web scraper locally, follow these steps:

1. Clone the repository to your local machine using the following command:
```git clone https://github.com/eniayejudaniel/Van-Listings-Web-Scraper-and-Data-Management```

2. Navigate to the project directory:
   ```cd van-listings-web-scraper-and-data-management```
   
3. Install the required dependencies using pip:
```pip install -r requirements.txt```

4. Make sure you have the necessary drivers for Selenium. By default, the project is set up to use ChromeDriver. If you prefer a different browser, download the appropriate driver and update the `webdriver` initialization in the `Van Listings Web Scraper and Data Management-checkpoint.ipynb` file.

5. Obtain your Google Sheets API credentials file (`credentials.json`) and place it in the project directory.

## Usage

1. Open the `Van Listings Web Scraper and Data Management-checkpoint.ipynb` file and set the desired configuration options:
- `url`: The URL of the website to scrape.
- `pages_to_scrape`: The number of pages to scrape. Adjust this value based on your requirements.
- `spreadsheet_name`: The name of the Google Sheets document to store the scraped data.

2. Run the script using the following command:
   ```python Van Listings Web Scraper and Data Management-checkpoint.ipynb```

3. The script will start scraping the van listings and display progress updates in the console. Once completed, it will print a success message and indicate the number of scraped vans.

4. You can access the scraped data in the Google Sheets document specified in the configuration. Make sure you have the necessary permissions to access and view the document.

## Technologies Used

- Python
- Selenium
- ChromeDriver
- gspread
- OAuth2Client
- Google Sheets API

## Contributing

Contributions to this project are welcome! If you encounter any issues or have suggestions for improvements, please feel free to submit a pull request or open an issue. Let's collaborate to make this project even better.

## License

This project is licensed under the [MIT License](LICENSE).



