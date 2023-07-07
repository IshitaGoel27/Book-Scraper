


# Book Scraper

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Screenshots](#screenshots)
- [Launch](#launch)
- [Technologies](#technologies)

## Introduction
Book Scraper is a python application that scrapes the book catalogue website, http://books.toscrape.com. It then allows you to look at the data related to books on the different pages of the website.

The purpose of this application was to become more familiar with web scraping.

## Features
- Scrapes the web site: http://books.toscrape.com
- Asynchronous requests
- Console menu with the options:
    - Look at highest rated books
    - Look at cheapest books
    - Get next available book in catalogue
    - Exit menu
- Console menu also has a progress bar



## Launch
To run, in the console enter:
```
python app.py
```

## Technologies
- [Python 3.8.3](https://www.python.org/downloads/release/python-383/)
### Python Modules
- [BeautifulSoup4](https://pypi.org/project/beautifulsoup4/)
    - Allows a web page to be scraped (parses its HTML or XML)
- [requests](https://pypi.org/project/requests/)
    - Allows sending HTTP requests
- [logging](https://docs.python.org/3/library/logging.html)
    - Allows for logging information.
- [asyncio](https://docs.python.org/3/library/asyncio.html)
    - For using event loops.
- [aiohttp](https://docs.aiohttp.org/en/stable/)
    - For creating asynchronous HTTP Client/Server connections with asyncio.
- [async_timeout](https://pypi.org/project/async-timeout/)
    - Asyncio-compatible timeout context manager.
        - Timeouts requests that take too long.
- [time](https://docs.python.org/3/library/time.html)
    - For timing code execution time.
