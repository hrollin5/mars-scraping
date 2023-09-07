# Mars Scraping
This project highlights the following technical skills:
* Automated browsing using Splinter
* HTML parsing with Beautiful Soup
* Casting data to correct types in a Pandas DataFrame
* Data analysis and visualization using matplotlib

## Objective
This new assignment consists of two technical products. You will submit the following deliverables:
* Deliverable 1: Scrape titles and preview text from Mars news articles.
* Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

### Data
Data were extracted from the following web pages. Accessed September 01, 2023
      https://static.bc-edx.com/data/web/mars_news/index.html
      https://static.bc-edx.com/data/web/mars_facts/temperature.html

### Technologies Used
* Splinter
* Beautiful Soup
* MatPlotLib
* Pandas

## Results
The two deliverables can be found in the Output folder. 
| <img width="1020" alt="Screenshot 2023-09-06 at 11 31 30 PM" src="https://github.com/hrollin5/mars-scraping/assets/130103105/10613849-c1d6-49ea-935a-ca59bc7680ae">| 
|:--:|
| An example of the JSON file with article titles and summaries |

### Weather Analysis
The following questions are answered in the weather_analysis Jupyter Notebook
1. How many months exist on Mars?
2. How many Martian (and not Earth) days' worth of data exist in the scraped dataset?
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
    * Find the average minimum daily temperature for all of the months.
    * Plot the results as a bar chart.
4. Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
    * Find the average daily atmospheric pressure for all the months.
    * Plot the results as a bar chart.
5. About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
    * Consider how many days elapse on Earth in the time that Mars circles the Sun once.
    * Visually estimate the result by plotting the daily minimum temperature.

