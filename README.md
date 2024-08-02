# Car Sales Data Analysis on Facebook Marketplace

This project involves web scraping and data analysis on car sales listings from Facebook Marketplace. The goal is to extract useful insights such as average price, average kilometrage, and the number of listings per year for a specific make and model of car.

## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Parameters](#parameters)
- [Insights](#insights)
- [Results](#results)
  
## Introduction
This project scrapes car listings from Facebook Marketplace using Beautiful Soup (BS4) and Splinter, processes the data with Pandas, and visualizes the results with Matplotlib. It focuses on analyzing various aspects such as the average price, average kilometrage, and the number of listings by year for a specific car make and model.

## Technologies Used
- **Beautiful Soup (BS4)**: For web scraping
- **Splinter**: For browser automation and web scraping
- **Pandas**: For data manipulation and analysis
- **Matplotlib**: For data visualization

## Parameters
You can change the results by modifying the following parameters in the script:
- `min_price`: Minimum price of the car listings (default: 1000)
- `max_price`: Maximum price of the car listings (default: 30000)
- `days_listed`: Number of days the listing has been on the marketplace (default: 7)
- `min_mileage`: Minimum kilometrage of the car listings (default: 50000)
- `max_mileage`: Maximum kilometrage of the car listings (default: 200000)
- `min_year`: Minimum year of the car listings (default: 2000)
- `max_year`: Maximum year of the car listings (default: 2020)
- `transmission`: Type of transmission (default: "automatic")
- `make`: Car make (default: "Honda")
- `model`: Car model (default: "Civic")

Note: Toronto is used as the location due to the lack of pricing information in the Algerian market.

## Insights
The main insights derived from the analysis include:
- **Average Price by Year**: The average price of the car listings by year.
- **Average Kilometrage by Year**: The average kilometrage of the car listings by year.
- **Number of Listings by Year**: The number of car listings by year.

## Results
The results of the analysis are visualized using bar charts:
- Average Price by Year
- Average Kilometrage by Year
- Number of Listings by Year

These visualizations help to understand trends in pricing, usage, and availability of the specified car make and model over the years.
