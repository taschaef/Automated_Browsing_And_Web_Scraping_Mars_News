# Mars_Scraping-Challenge

In this assignment I was asked to preform a full web-scraping and data analysis project. I've learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. I’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

Throughout on this Challenge, I strengthened the same core skills that I’ve been developing: collecting data, organizing and storing data, analyzing data, and then visually communicating insights.

# What I've Created
This new assignment consists of two technical products:

Deliverable 1: Scrape titles and preview text from Mars news articles.

Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

Deliverable 3: CSV file created in the Mars_Weather Deliverable. 

Deliverable 1 can be found under the name Mars_News. Deliverable 2 can be found under the name Mars_Weather. Finally Deliverable 3 can be found under the name Mars_Weather_data.csv. 

# Deliverable 1 - Mars News
Part 1: Scrape Titles and Preview Text from Mars News
* Open the Jupyter Notebook in the starter code folder named part_1_mars_news.ipynb. You will work in this code as you follow the steps below to scrape the Mars News website.
* Use automated browsing to visit the Mars news siteLinks to an external site.
* Inspect the page to identify which elements to scrape.
* Create a Beautiful Soup object and use it to extract text elements from the website.
* Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows: Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview.
* Store all the dictionaries in a Python list.
* Print the list in your notebook.

# Deliverable 2 - Mars Weather 
Part 2: Scrape and Analyze Mars Weather Data
* Open the Jupyter Notebook in the starter code folder named part_2_mars_weather.ipynb. You will work in this code as you follow the steps below to scrape and analyze Mars weather data.
* Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.
* Inspect the page to identify which elements to scrape. 
* Create a Beautiful Soup object and use it to scrape the data in the HTML table.
* Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website.
* Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.
* Analyze your dataset by using Pandas functions to answer the following questions:

1. How many months exist on Mars?
2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
  * Find the average minimum daily temperature for all of the months.
  * Plot the results as a bar chart.
4. Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
5. Find the average daily atmospheric pressure of all the months.
  * Plot the results as a bar chart.
6. About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
  * Consider how many days elapse on Earth in the time that Mars circles the Sun once.
  * Visually estimate the result by plotting the daily minimum temperature.
 
 # Deliverable 3 - CSV file
 * Export the DataFrame to a CSV file
