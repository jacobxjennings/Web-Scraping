# Web-Scraping

## Overview
Here we use Python, Splinter, Beautiful Soup, and others to scrape webpages for news stories. Additionally, we scrape data for Martian weather patterns. 

### Part One

We use Beautiful Soup to automatically scrape articles, logging the headline and summary into a dictionar.

![JSON](https://github.com/jacobxjennings/Web-Scraping/blob/main/JSON_Data.PNG?raw=true)

### Part Two

Here we used Panda to scrape the ttarget website since it's already a table. 

**How many Months are there on Mars?**

We use `nunique()` to determine there are 12 months on Mars. 

**What is the average low temperature by month?**

First we get the mean, min, and max of the min_temp to determine that month 3 is the coldest month, on average. 

![Min_temp_avg_monthly](https://github.com/jacobxjennings/Web-Scraping/blob/main/avg-min-temp-monthly.png?raw=true)

**What is the average pressure per month?**

We can use the same process as above to determine this. 

![Average_Pressure](https://github.com/jacobxjennings/Web-Scraping/blob/main/avg-monthly-pressure.png?raw=true)