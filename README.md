# web-scraping-challenge

#### This challenge is part of the Data Analytics and Visualization bootcamp through the University of Minnesota.

## This assignment consists of two technical products. You will submit the following deliverables:

  Deliverable 1: Scrape titles and preview text from Mars news articles. (part_1_mars_news.ipynb)

  Deliverable 2: Scrape and analyze Mars weather data, which exists in a table. (part_2_mars_weather.ipynb)

### Part 1: Scrape Titles and Preview Text from Mars News (part_1_mars_news.ipynb)

  1. Use automated browsing to visit the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape.

  2. Create a Beautiful Soup object and use it to extract text elements from the website.

  3. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:

      - Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. 
  
      - Store all the dictionaries in a Python list.

      - Print the list in your notebook.


### Part 2: Scrape and Analyze Mars Weather Data (part_2_mars_weather.ipynb)

  1. Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.

  2. Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.

  3. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. 

  4. Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.

  5. Analyze your dataset by using Pandas functions to answer the following questions:

    - How many months exist on Mars?
    
    - How many Martian (and not Earth) days worth of data exist in the scraped dataset?
    
    - What are the coldest and the warmest months on Mars (at the location of Curiosity)? 

    - Which months have the lowest and the highest atmospheric pressure on Mars?

    - About how many terrestrial (Earth) days exist in a Martian year?
    
  6. Export the DataFrame to a CSV file.

# References
