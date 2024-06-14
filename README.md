
# Allocine top movies : Web Scraping to BI Dashboards

## Description
This project focuses on scraping data from Allocine's website, cleaning and transforming the data using SSIS and Talend, and finally building a comprehensive report using Power BI. The goal is to extract meaningful insights and trends from Allocine's movie data.

## Table of Contents
1. [Installation](#installation)
2. [Web-Scraping](#Web-Scraping)
3. [Data-Cleaning](#Data-Cleaning)
4. [Report-Building](#Report-Building)

## Installation
To run this project locally, follow these steps:
1. Clone the repository to your local machine.
2. Install SSIS and Talend for data cleaning.
3. Install Power BI Desktop for report building.
4. Open the project files in the respective tools.

## Web-Scraping
The data scraping process involves extracting information such as movie titles, ratings, directors, and other relevant data from Allocine's website using BeautifulSoup library of python.Modify the value of the variable 'locationOfScrapedData' in the Jupyter file to select the destination for scraped data.

## Data-Cleaning
Data cleaning is performed using SSIS and Talend (same workflow)to preprocess the scraped data. This includes standardizing formats, and ensuring data quality.
SSIS package :
![Package SSIS](https://github.com/OurachSoumiya/Allocine-dashboard/assets/132670569/a4c93624-af2c-4659-bba1-3e60eee2992c)
Talend packages :
![talend cleaning](https://github.com/OurachSoumiya/Allocine-dashboard/assets/132670569/3f32fdfe-c088-4b07-9ffb-8ac68218dbec)
![talend aggregatiions](https://github.com/OurachSoumiya/Allocine-dashboard/assets/132670569/6f4b0e7a-e7eb-4448-976b-73269ac05fa1)


## Report-Building
The cleaned data is then used to build interactive and visually appealing reports using Power BI. These reports provide insights into trends, user preferences, and other key metrics related to movies.

![page1](https://github.com/OurachSoumiya/Allocine-dashboard/assets/132670569/ef59abe0-2a5a-4c35-868b-7b8509457ee4)
![page2](https://github.com/OurachSoumiya/Allocine-dashboard/assets/132670569/71d8a55d-1604-4a93-8a3a-3a5b405607b4)
