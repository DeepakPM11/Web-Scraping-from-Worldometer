# Web-Scraping-from-Worldometer
Collecting the Covid 19 Data from worldometer and it s manipulation
Data is scraped from https://www.worldometers.info/coronavirus/ 

Using Requests we create a connection and get the html data.
Using Beautifulsoup we remove the tags and filter out the required data as lists or arrays and combine it into a dataframe.

We manipulate this data to find the populaiton : No. of Tests ratio
and plot the trends using bar graph (matplotlib).
