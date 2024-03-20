
# Allocine top movies : Data Scraping to BI Dashboards

## Description
This project focuses on scraping data from Allocine's website, cleaning and transforming the data using SSIS and Talend, and finally building a comprehensive report using Power BI. The goal is to extract meaningful insights and trends from Allocine's movie data.

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Contributing](#contributing)
4. [License](#license)

## Installation
To run this project locally, follow these steps:
1. Clone the repository to your local machine.
2. Install SSIS and Talend for data cleaning.
3. Install Power BI Desktop for report building.
4. Open the project files in the respective tools.

## Data Scraping
The data scraping process involves extracting information such as movie titles, ratings, directors, and other relevant data from Allocine's website using BeautifulSoup library of python.(open jupyter file and change the value of the variable 'locationOfScrapedData' to choose the destination of scraped data)

## Data Cleaning
Data cleaning is performed using SSIS and Talend (same workflow)to preprocess the scraped data. This includes standardizing formats, and ensuring data quality.

## Report Building
The cleaned data is then used to build interactive and visually appealing reports using Power BI. These reports provide insights into trends, user preferences, and other key metrics related to movies.