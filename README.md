# Zillow_Scraper
I recently just completed a Python course on Udemy and I wanted to build my own project from stratch. I wanted the project to be meaningful and impactful to me, and since I am considering moving from my current apartment, I wanted to know what other apartments/homes are renting for in the city I live in(Arlington Tx). I decided to build a webscraper that grabs all the listing info for places being put up for rent on Zillows website and writes it all out to a CSV file using Pandas.

## Features 
The code is currently hard coded to Arlington Tx, but it can be easily formmated to the city and state you want to scrape.
* Grabs all the listing info in specified city 
* Writes the Name,Details(price,bedroom,sqft), Address to a CSV file

## Install
Use the following pip command:
* pip install selenium
* pip install pandas 
* chromedriver
