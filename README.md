
# Web Scraping and Data Analysis
This repository contains a Python script for web scraping and data analysis from a list of URLs. The script utilizes the requests library to make GET requests to each URL, and the BeautifulSoup library to parse the HTML content of the web pages.

# Installation
Clone the repository to your local machine.
Install the required libraries by running pip install -r requirements.txt.
# Usage
Ensure that you have the list of URLs in an Excel file (blackcoffer websites link dataset.xlsx in this case).
Run the extract_data_in_txt function to extract data from a single URL and save it in a text file.
Run the create_files function to extract data from all URLs in the Excel file and save them in separate text files.
Stop words for data analysis are stored in separate text files in the StopWords_ directory. These files are used to filter out common stop words from the extracted text data.
# Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.
