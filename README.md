# <div align="center">Custom WebScrapers' Repository</div>

<p align="justify">This repository contains codes for web scraping, a technique for extracting data from websites. It's important to note that web scraping should always be conducted ethically and in accordance with the terms of service and privacy policies of the targeted websites. The codes provided in this project are designed solely for educational and research purposes to demonstrate the process of web scraping. They target publicly accessible data while adhering to the privacy standards of the platforms being scraped. However, it's essential to understand that website policies may change, and scraping data without permission or against a website's terms of service could potentially violate legal or ethical standards. If any code provided in this project is found to be in violation of a website's policy, it will be promptly removed upon notification.</p>

## BBC News WebScraper

<p align="justify">The provided code extracts article data from BBC News. Ensure an active internet connection before executing the code. Set max_pages to the maximum number of pages to extract. All the articles on the page will be extracted, including "Heading", "Date", "Author", "Content", and "Link" for each article. All the extracted data is stored in pandas data-frame. A tqdm load-bar is added for time management while the code is executing.</p>

## BestBuy WebScraper

<p align="justify">The webscraper for BestBuy is divided into two parts. Initially, a webdriver is utilized to extract the links of the products from a specified number of pages, determined by the max_pages variable. The second part involves inputting a link, from which Heading, Model Number, SKU Number, Rating, Reviews, and Price of each product are extracted. Both functions are separately defined. To achieve an autonomous process of webscraping, the function that extracts links should be connected to the function that extracts data from the links, and the final output is stored in a pandas dataframe.</p>

## Business Recorder WebScraper

<p align="justify">The code below launches a web driver and retrieves data from the designated website, Business Recorder. For every article, it extracts the header, the datetime, the content type, the content, and the link. Until the maximum scroll is achieved, the code automatically scrolls down. A pandas data frame contains all of the extracted data. Collected links whose data could not be recovered because of error 403 are shown by the end of the code if you chose to display them.</p>

## CNBC WebScraper

<p align="justify">The following loops retrieve information from the HTML file, including each article's title, author, content type, date, content, and link. Prior to running the code, make sure the internet is active. Included for effective time management during code execution is a tqdm loadbar. A pandas dataframe will hold all of the extracted data. The max_links_to_collect informs the code of how many articles to scrape. (If ' Max Try Exceeded: Reconnection Error ' occurs, perform a DNS flush by entering the required command in your terminal / command prompt.)</p>

## Yahoo Finance WebScraper

<p align="justify">To navigate down the Yahoo Finance page, press and hold the space key on your keyboard. Continue holding it until you reach the maximum scroll. Once you've reached the bottom, download the webpage as an HTML file. Finally, upload the downloaded file to the program. The provided loop extracts data from the HTML file, including the title, author, datetime, readtime, content, tags, and link of each article. Ensure an active internet connection before executing the code. A tqdm loadbar is incorporated to enhance time management during code execution. All the extracted data will be stored in a pandas dataframe.</p>

### Programming Language:

- **Python**

### Environments Used:

- **Jupyter Notebook**
- **Google Colab**
