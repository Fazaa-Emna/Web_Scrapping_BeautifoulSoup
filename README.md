# Rugby_Stats

Exploring international rugby union scoring statistics through data gathered from ESPN's StatsGuru.

## Overview

This project focuses on analyzing rugby union data from various countries. The available data includes scoring stats for international teams, processed to allow for deeper analysis and insights.

## Project Files

- **`countries.csv`**: Contains a comprehensive list of countries participating in international rugby, along with their respective tiers and any relevant abbreviations.
  
- **`preprocessed.csv`**: This dataset is the result of preprocessing the raw data (`rugby_stats_final.csv`) using the `PreProcessingScript.R`. It includes newly derived features aimed at enhancing analytical capabilities.
  
- **`PreProcessingScript.R`**: An R script designed to preprocess the scraped data and introduce additional features that can be leveraged in further analyses.
  
- **`rugby_stats_final.csv`**: The raw dataset scraped from ESPN's StatsGuru, capturing various rugby union statistics.
  
- **`scraper.py`**: A Python script employing `BeautifulSoup` for web scraping the data from ESPN's StatsGuru platform.

- **`README.md`**: This document provides an overview of the project, its contents, and supplementary resources.

## Additional Resources

For more context and details on international rugby teams and their tiers, refer to the following resources:

- Rugby Internationals Tier List: [Wikipedia - List of International Rugby Union Teams](https://en.wikipedia.org/wiki/List_of_international_rugby_union_teams)
- ESPN StatsGuru Rugby Database: [StatsGuru](http://stats.espnscrum.com/statsguru/rugby/stats/index.html)
