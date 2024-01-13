
# Web Scraping Nepali Movie Data from Film Development Board of Nepal

This Python script demonstrates how to perform web scraping to extract Nepali movie data from the Film Development Board of Nepal's website using BeautifulSoup.

## Requirements

Make sure you have the following dependencies installed:

- Python 3.x
- BeautifulSoup (`pip install bs4`)
- Requests (`pip install requests`)

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/sandesh034/NMDB_WEB_SCRAPPING.git
   cd NMDB_Scrapping
   ```

2. Run the notebook:

   ```bash
   nepali_movieDB_scrapping.ipynb
   ```

## Script Explanation

The script performs the following steps:

1. Sends a request to the [Film Development Board of Nepal](https://nmdb.film.gov.np/) website.
2. Retrieves the HTML content of the webpage.
3. Uses BeautifulSoup to parse the HTML and extract information about Nepali movies.
4. Saves the extracted data to json file

## Disclaimer

This script is created solely for educational purposes to demonstrate web scraping techniques using BeautifulSoup in Python. The intention is to learn and practice web scraping skills in a controlled environment.

Users of this script should be aware of and comply with the terms of use of the [Film Development Board of Nepal](https://nmdb.film.gov.np/) website. Misuse of the script, including but not limited to unauthorized access, excessive requests, or any activity violating the terms and conditions of the website, is strictly prohibited.

The creators and contributors to this script are not responsible for any misuse of the data obtained through this scraping process. Users are solely responsible for their actions and are advised to use the script in accordance with legal and ethical standards.

## Contribution

Feel free to modify and use the code according to your needs. If you find any issues or have suggestions for improvement, please open an issue or create a pull request.

Happy learning and scraping responsibly!
