# html-scraping-challenge
Data on news stories relevant to Mars were scraped from the following website: https://static.bc-edx.com/data/web/mars_news/index.html.

Raw data on daily temperature recordings (in degrees Celsius) on Mars over a 5.5 year period from 16 August 2012 to 27 February 2018 taken from NASA's Curosity rover was scraped from the following website: https://static.bc-edx.com/data/web/mars_facts/temperature.html


## Project Description:
After scraping, raw temperature data has been saved as **mars_dataframe.csv**, located within the **Raw Data** subfolder. 

## Installation and Run Instructions:
Executing the script provided in the **part_1_mars_news.ipynb** file, located in the **Starter_Code** subfolder, will output the following:
1. Extracts of the titles and preview text of the news articles relevant to Mars.

Executing the script provided in the **part_2_mars_weather** file, located in this same subfolder, will output the following:
1. Number of months on Mars
2. Number of Martian (and not Earth) days worth of data exist in the scraped dataset
3. Coldest and the warmest months on Mars
4. Which months have the lowest and the highest atmospheric pressure on Mars
5. About how many terrestrial (Earth) days exist in a Martian year
   

## Credits:
This code was compiled and written by me for the pymaceuticals challenge class homework in the 2024 Data Analytics Boot Camp hosted by Monash University. Additional credits are declared below:


### Parsing cells of a table, rather than whole rows:
https://stackoverflow.com/questions/23377533/python-beautifulsoup-parsing-table (accessed 12 May 2024).
