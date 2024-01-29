# datacollection_challenge
Data collection and web scraping challenge

Part 1: Scrape Titles and Preview Text from Mars News

1. Used automated browsing to visit the [Mars news site](https://static.bc-edx.com/data/web/mars_news/index.html)
2. Created a Beautiful Soup object and used it to extract text elements from the website.
3. Extracted the titles and preview text of the news articles scraped. Stored the results in Python data structures and exported to a json file.

Part 2: Scrape and Analyze Mars Weather Data

1. Used automated browsing to visit the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html)
2. Created a Beautiful Soup object and used it to scrape the data in the HTML table and assembled into a Pandas dataframe.
3. Converted the datatypes for all of the columns  as necessary except the 'id' column. 
4. Did the analysis of the following questions:
    - How many months exist on Mars? 
        > Calculated the month count data.

    - How many Martian (and not Earth) days worth of data exist in the scraped dataset?
        > 1867

    - What are the coldest and the warmest months on Mars (at the location of Curiosity)?
        > From the bar plot, it appears that the coldest month seems to be the third month as it has the lowest temperature and the hottest month seems to be the eighth   month as it is has the highest temperature on Mars, on average. Either ways, the temperature is a lot colder compared to Earth.

    - Which months have the lowest and the highest atmospheric pressure on Mars?
        > From the bar plot, on average, the sixth month seems to have the lowest and the ninth month seems to have the highest atmospheric pressure.

    - About how many terrestrial (Earth) days exist in a Martian year?
        > From the plot of number of terrestrial days by minimum temperature, the distance from peak to peak is roughly 1425-750 = 675 days. A year on Mars appears to be about 675 days.

