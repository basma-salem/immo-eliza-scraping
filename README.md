# immo-eliza-scraping
            ![brand-logo](https://github.com/user-attachments/assets/ed79ce86-29b6-4252-9103-7849d1edc05d)

## 🏢 Description

This project is an asynchronous web scraper designed to extract property data from the **Immo Liza** real estate website (`immo-liza.be`). The goal is to scrape property listings and details like titles, prices, descriptions, and other relevant information, then store the data in a CSV file for further analysis or processing.

The project is built using Python with `aiohttp` for asynchronous HTTP requests, `pandas` for CSV file manipulation, and `BeautifulSoup` for parsing HTML.

## Features

- Efficient asynchronous web scraping with `aiohttp`.
- Customizable data extraction using `BeautifulSoup`.
- Supports scraping large numbers of URLs concurrently.
- Saves scraped data to CSV for easy data analysis.

## Prerequisites

Before running the project, make sure you have the following tools and libraries installed:

- Required Python packages:
  - `aiohttp`
  - `pandas`
  - `beautifulsoup4`

## 📦 Repo structure

```
.
├── src/
├── data
    ├── filterd_urls.csv
    ├── final_properties.csv
├── scraper
├── xml_files
    ├── extracted_urls.csv
├── .gitignore
├── venv
├── main.py
├── requirements.txt
└── README.md
```
## 🛎️ Usage

1. Clone the repository to your local machine.

2 .To run the script, you can execute the `main.py` file from your command line:

    ```
    python main.py
    ```

3.The script reads XMls root data the filters  to get Appartments / Houses for sales save the filterd data in CSV file 
the use this file to scarp the filtered URL to get data from each URL such ( id , price , type of sale , living area ,...etc) using asynco and finally stores this data set in CSV file . 

```python

```
## ⏱️ Timeline

This project took 5 days for completion.

## 📌 Personal Situation
This project was done as part of the AI Boocamp at BeCode.org. 

Connect with me on [LinkedIn](www.linkedin.com/in/basma-salem-ba45a1113).
