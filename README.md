# M11-Data-Collection-Challenge

This endeavor encompasses the extraction of Mars-related news articles and Mars weather data, followed by a comprehensive analysis of the gathered information. The process of scraping and analyzing the data has been segregated into two distinct components.

**Requirements**
- Python v3.10.9
- Install Numpy
- Install Pandas
- Install Datetime
- Install Matplotlib
- Import seaborn
- From splinter import Browser
- From bs4 import BeautifulSoup as soup
- Import json

**Part 1: Scrape and Analyze Mars Weather Data**

Here are the steps involved in this task:

1. Begin by accessing the specified Jupyter Notebook file, named "part_1_mars_news.ipynb." This particular notebook will serve as the foundation for executing the Mars news scraping procedure.

2. Utilize automated browsing techniques to navigate to the Mars news website and carefully examine the webpage's structure. This step is essential in order to identify the specific elements that need to be extracted.

3. Proceed to extract the titles and preview text of the news articles from the website. Store the retrieved information in appropriate Python data structures. To accomplish this, create a Python dictionary for each title-and-preview pair, assigning the keys 'title' and 'preview' to the respective values.

4. Consolidate all the created dictionaries into a single Python list. This list will hold all the extracted data, allowing for easier management and further analysis.

5. Display the list of scraped data within the Jupyter Notebook by printing it. Additionally, save the output as a JSON file named "Title_Preview.JSON" for future reference and easy access.

**Part 2: Design Your Climate App**

1. Access the Jupyter Notebook file named "part_2_mars_weather.ipynb" located in the provided starter code folder. This particular notebook is dedicated to the task of scraping and analyzing Mars weather data.

2. Utilize automated browsing techniques to navigate to the Mars Temperature Data website, which can be found at the URL: https://static.bc-edx.com/data/web/mars_facts/temperature.html. Thoroughly examine the webpage's structure to identify the specific elements that need to be extracted.

3. Organize the scraped data into a Pandas DataFrame, ensuring that the columns align with the headings of the table present on the website.

4. Engage in the following analyses using the obtained Mars weather data:

- Determine the count of months existing on Mars.
- Calculate the number of Martian days' worth of data available in the scraped dataset.
- Identify the coldest and warmest months on Mars at the Curiosity location by computing the average minimum daily temperature for each month. Visualize the results by creating a bar chart.
- Identify the months with the lowest and highest atmospheric pressure on Mars by calculating the average daily atmospheric pressure for each month. Present the findings using a bar chart.
- Estimate the number of terrestrial (Earth) days in a Martian year by visually examining the daily minimum temperature data and considering the time it takes for Mars to complete one orbit around the Sun.
- Export the DataFrame containing the analyzed data to a CSV file for further reference.

**References**

The Mars News websiteLinks to an external site. is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from NASA's Mars NewsLinks to an external site. website in November 2022. Images are used according to the JPL Image Use PolicyLinks to an external site., courtesy NASA/JPL-Caltech.
