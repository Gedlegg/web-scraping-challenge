# web-scraping-challenge

## Overview
The analysis utilizes splinter, bs4, Pandas, and Matplotlib to scrape website, analyze and visualize data. It is divided into two parts: part 1 involves scrape titles and preview text from Mars news articles and Part 2 focuses scrape and analyze Mars weather data, which exists in a table.

## Part 1: Scrape titles and preview text from Mars news articles
- Used automated browsing to visit the Mars news site.
- Created a Beautiful Soup object and used it to extract text elements from the website.
- Extracted the titles and preview text of the news articles and stored the scraping results in Python dictionary and print the list.
## part 2: Scrape and analyze Mars weather data, which exists in a table.
- Used automated browsing to visit the Mars Temperature Data Site.
- Created a Beautiful Soup object and used it to scrape the data in the HTML table.
- Assembled the scraped data into a Pandas DataFrame.
- Examined the data types that are currently associated with each column and converted the data to the appropriate data types.
- The data was analyzed to answer the following questions, and a data visualization was created to support each answer:
    - Which month, on average, has the lowest temperature?
    - Which month, on average, has the lowest atmospheric pressure?
    - How many terrestrial days exist in a Martian year?
- Export the DataFrame to a CSV file.