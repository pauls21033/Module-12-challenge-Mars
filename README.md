# Module-12-challenge-Mars
Deliverable 1: Scrape Titles and Preview Text from Mars News (40 points)
Deliverable 1 Instructions
Create a new Jupyter notebook named mars_data_challenge_part_1.ipynb.

Scrape the Mars News (Links to an external site.) website by using Splinter and Beautiful Soup. Specifically, scrape the title and preview text, or summary text, of each article on the landing page.

Deliverable 1 Requirements
Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup). (10 points)

The titles and preview text of the news articles were scraped and extracted. (20 points)

The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries. (10 points)

Deliverable 2: Scrape and Analyze Mars Weather Data (60 points)
Deliverable 2 Instructions
Create a Jupyter notebook named mars_data_challenge_part_2.ipynb. Import the relevant dependencies for web scraping, Pandas, and Matplotlib.

With your automated browser, visit the Mars Temperature Data (Links to an external site.) site. Note that the URL is https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html.

Scrape the data in the HTML table. To do so, choose one of two ways. The first, simpler way is to use Pandas's read_html method. The second, slightly more challenging way is to manually scrape the data by using Splinter and Beautiful Soup. We highly encourage you to choose the latter to reinforce your scraping skills.

Answer the following question: How many months exist on Mars?

Answer the following question: How many Martian (and not Earth) days worth of data exist in the scraped dataset?

Answer the following question: What are the coldest and the warmest months on Mars (at the location of Curiosity)? Get the answer by averaging the minimum daily temperature of all the months. Plot the results as a bar chart.

Answer the following question: Which months have the lowest and the highest atmospheric pressure on Mars? Get the answer by averaging the daily atmospheric pressure of all the months. Plot the results as a bar chart.

Answer the following question: About how many terrestrial (Earth) days exist in a Martian year? That is, in the time that Mars circles the Sun once, how many days elapse on Earth? Visually estimate the result by plotting the daily minimum temperature.

Export the DataFrame to a CSV file.

Deliverable 2 Requirements
The HTML table was extracted into a Pandas DataFrame. Either Pandas or Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types. (15 points)

The data was analyzed to answer the following questions, and a data visualization was created to support each answer: (40 points)

How many months exist on Mars?
Which month, on average, has the lowest temperature? The highest?
1411	2016-10-15	1490	241	9	-66.0	904.0
Which month, on average, has the lowest atmospheric pressure? The highest?
How many terrestrial days exist in a Martian year? A visual estimate within 25% was made.
The DataFrame was exported into a CSV file. (5 points)
