# Exploratory_Data_Analysis_netflix
## Netflix Data Analysis with Python
This Colab notebook explores the Netflix shows and movies dataset obtained from Flixable using opendatasets. The analysis focuses on:

+ Data Cleaning:
+ Handling missing values in various columns.
+ Converting date_added to datetime format.
+ Exploratory Data Analysis:
+ Visualizing the distribution of show types (movies vs. TV shows).
+ Examining the top countries with shows on Netflix.
+ Analyzing the most frequent ratings for shows.
+ Exploring the top listed-in categories.

## Libraries Used:

*pandas*: Data manipulation and analysis.
*numpy*: Mathematical operations.
*opendatasets*: Downloading datasets.
*seaborn*: Data visualization.
*matplotlib*: Additional plotting utilities (imported in some cells).

## Running the Notebook:

Access the Dataser: https://www.kaggle.com/datasets/shivamb/netflix-shows

Run the Cells: Execute the code cells within the notebook (follow any specific instructions provided).

## Data Cleaning:

Missing values are identified and filled with placeholders like 'Unavailable' for relevant columns.
date_added is converted to a datetime format.

## Observations:

+ The dataset contains more movies than TV shows.
+ The United States has the most shows on Netflix, followed by India and several other countries.
+ TV-MA and TV-14 are the most frequent ratings on Netflix.
+ Many shows fall under various listed-in categories.

## Further Exploration:

+ Analyze the relationship between release year and show type (movie vs. TV show).
+ Explore the duration distribution for shows.
+ Investigate sentiment analysis of show descriptions.

## Note:

This is a basic exploration based on the provided code snippets. You can extend the analysis with additional visualizations and insights.
