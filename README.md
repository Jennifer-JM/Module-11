# Module-11

---

# Mars Web Scraping and Data Analysis

## Overview

This project involves web scraping and data analysis to explore Mars-related information. Utilizing tools like Splinter, Beautiful Soup, and Pandas, the project extracts data from two different sources and presents insights through data visualization. The primary goal is to sharpen web scraping, data organization, and analysis skills while visually communicating findings

---

## Deliverables

### Part 1: Scrape Titles and Preview Text from Mars News

- **Objective**: Extract the titles and preview text of Mars news articles from the [Mars News website](https://redplanetscience.com)
- **Process**:
  - Automated browsing was implemented using **Splinter** to navigate the webpage
  - **Beautiful Soup** was used to parse the HTML content and extract relevant text elements
  - Each article's `title` and `preview` text were stored as a dictionary with two keys (`title`, `preview`)
  - All dictionaries were collected into a list for easy handling
  - The scraped data was optionally exported to a JSON file for data sharing
- **Outcome**: A Python list containing the titles and previews of Mars news articles

---

### Part 2: Scrape and Analyze Mars Weather Data

- **Objective**: Extract and analyze Mars weather data from the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html)
- **Process**:
  - **Beautiful Soup** was used to scrape an HTML table containing weather data for Mars
  - The data was assembled into a **Pandas DataFrame**
  - Data types were converted to appropriate formats (e.g., `datetime`, `int`, `float`)
  - The dataset was analyzed to answer the following questions:
    1. **How many months exist on Mars?**
    2. **How many Martian days' worth of data exist?**
    3. **What are the coldest and warmest months on Mars?**
       - Average minimum daily temperature was calculated for each month
       - Results were visualized using a bar chart
    4. **Which months have the lowest and highest atmospheric pressure on Mars?**
       - Average daily atmospheric pressure was calculated for each month
       - Results were visualized using a bar chart
    5. **How many terrestrial days exist in a Martian year?**
       - Daily minimum temperatures were plotted to visually estimate the number of Earth days in a Martian year
  - The DataFrame was exported to a CSV file for future use
- **Outcome**:
  - A comprehensive DataFrame of Mars weather data
  - Visualizations to highlight temperature and atmospheric pressure trends
  - An estimate of the length of a Martian year in Earth days

---

## Tools and Technologies

- **Splinter**: Automated browsing to navigate web pages
- **Beautiful Soup**: HTML parsing and element extraction
- **Pandas**: Data manipulation and analysis
- **Matplotlib**: Data visualization
- **Jupyter Notebook**: Interactive environment for coding and analysis
- **CSV**: Exported DataFrame for further use

---

## Results

1. **Mars News Titles and Previews**:
   - Extracted and stored as a structured Python list for easy access and usage
2. **Mars Weather Data Analysis**:
   - Identified key patterns in temperature and atmospheric pressure
   - Determined the coldest and warmest months as well as the months with the lowest and highest pressure
   - Estimated the number of terrestrial days in a Martian year

---

## File Structure

- **part_1_mars_news.ipynb**: Notebook for scraping Mars news articles
- **part_2_mars_weather.ipynb**: Notebook for scraping and analyzing Mars weather data
- **mars_weather.csv**: Exported DataFrame containing Mars weather data

---

## Skills Demonstrated

- Web scraping with automated browsing and HTML parsing
- Data cleaning, transformation, and organization with Pandas
- Visualizing insights using Matplotlib
- Exporting data for reproducibility and sharing

---
