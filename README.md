# Exploring Mars Data

Part 1: Mars News

In part 1 of this project, I used automated browsing to visit the Mars NASA news site and inspected the page to identify which elements to scrape. Then, I created a Beautiful Soup object and used it to extract the titles and preview text of the news articles from the website.
I stored the scraping results in a Python dictionary which was then stored in a list and exported to a JSON file. 

Part 2: Mars Weather Data

In part 2 of this project, I used automated browsing to visit the Mars Temperature Data Site and inspected the page to identify which elements to scrape. Then, I created a Beautiful Soup object and used it to scrape the data in the HTML table. Next, I assembled the scraped data into a Pandas DataFrame and converted the data to the appropriate data types for analysis. I analyzed the following five questions:

1) How many months exist on Mars?
2) How many Martian (and not Earth) days worth of data exist in the scraped dataset?
3) What are the coldest and the warmest months on Mars (at the location of Curiosity)? 
4) Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
5) About how many terrestrial (Earth) days exist in a Martian year? 

After the analysis, I exported the dataframe into a CSV file.