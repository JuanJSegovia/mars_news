# Mars Web Scraping and Data Analysis Project
## Overview

The objective is to scrape data related to Mars from two separate websites and analyze it to answer specific questions. The project is divided into two main parts:

### Scraping Mars News: Extracting news titles and preview texts from a Mars news website.
### Scraping and Analyzing Mars Weather Data: Scraping a table of Mars weather data and performing analysis to uncover trends related to Martian climate.

# Deliverables

The project consists of two deliverables:

## Deliverable 1: Scrape Titles and Preview Text from Mars News

### Objective: Use automated browsing and web scraping to extract the titles and preview texts of the latest news articles from a Mars news website.

Approach:
The titles and preview texts were scraped using BeautifulSoup and Splinter.
Each title and preview was stored in a Python dictionary with two keys: title and preview.
The dictionaries were stored in a list, and the list was printed as a final output.

## Deliverable 2: Scrape and Analyze Mars Weather Data

### Objective: Scrape weather data from a table on a Mars weather site and analyze it to answer the following questions:
How many months exist on Mars?
How many Martian days' worth of data exist in the dataset?
Which months have the lowest and highest temperatures on Mars?
Which months have the lowest and highest atmospheric pressure?
How many Earth days exist in a Martian year?

Approach:
The weather data was scraped using BeautifulSoup.
The data was processed and stored in a Pandas DataFrame.
Data types were converted to appropriate formats (e.g., terrestrial_date to datetime, sol to integers).
Analysis was performed using Pandas functions and visualized using Matplotlib, including bar charts for temperature and pressure trends.

