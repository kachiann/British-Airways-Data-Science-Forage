## Task One: Web scraping to gain company insights <a name="task-one-web-scraping-to-gain-insights-on-british-airways"></a>
In this task, I scraped and analyzed customer review data to uncover findings for British Airways, then used PowerPoint to present my findings. Web scraping is the process of obtaining information from the Internet. The project involved the following steps:

- **Scraping Data from [Skytrax](https://www.airlinequality.com/)**: Extracting data directly from the Skytrax website.
- **Fetching HTML Code**: Using Python’s `requests` library to retrieve the site's HTML code for interaction.
- **Parsing HTML with Beautiful Soup**: Utilizing Beautiful Soup, a Python library, to parse and navigate the structured HTML data.
- **Analyzing the Data**: Given the messy and text-heavy nature of the collected data, extensive data cleaning was necessary to prepare it for analysis. This process included:
  - **Removing HTML Tags and Noise**: Stripping away unnecessary HTML tags and any irrelevant content to isolate the meaningful text.
  - **Standardizing Text**: Converting text to a uniform format by lowercasing, removing punctuation, and correcting spelling errors to ensure consistency.
  - **Tokenization and Stop Word Removal**: Breaking down text into individual tokens (words or phrases) and removing common stop words that do not contribute significant meaning to the analysis.
  - **Word Cloud Visualization**: Creating word clouds to visualize the most frequently occurring words in the reviews, providing a quick and intuitive understanding of common themes and sentiments.
  - **Sentiment Analysis**: Applying sentiment analysis techniques to determine the overall sentiment (positive, negative, neutral) of the reviews.
  - **Exploratory Data Analysis (EDA)**: Conducting EDA to uncover patterns, trends, and insights within the data, using visualization tools and statistical techniques to summarize and understand the dataset.

---
In my analysis, I incorporated Word Cloud and Sentiment Analysis. Topic Modeling can also be considered for a more comprehensive analysis.

This [Jupyter Notebook](https://github.com/kachiann/British-Airways-Data-Science-Forage/blob/main/Task%20One_Final.ipynb) contains the primary findings of my analysis.

### Task One Presentation
The summary of my findings is in this [PowerPoint slides](https://docs.google.com/presentation/d/1t3U0xZN3LkQUJwjmig79yqjeHQZeOaM7pmPgfIpApdg/edit?usp=sharing). Within the slides, I've crafted visualizations and metrics to convey the findings effectively.
