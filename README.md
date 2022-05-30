# Movies-ETL
ETL, Pandas, Python, Jupyter Notebook, PostgreSQL

## Project Overview
Within the scope of the Amazing Prime Hackathon, this project will create an automated pipeline that takes in new data, from Wikipedia data, Kaggle metadata and the MovieLens rating data. It then performs the appropriate transformations and loads the data into an existing PostgreSQL database usabel for the hackathon participants without giving undue access or risk to the company data and files.

For this analysis, we used the following breakdown:

- write an ETL function to read three data files,
- extract and transform the Wikipedia data,
- extract and transform the Kaggle and rating data,
- load the data to a PostgreSQL Movie Database.

# Resources
Data Source: wikipedia-movies.json, movies_metadata.csv, ratings.csv
Software: Python, Conda, Jupyter Notebook, PostgreSQL, pgAdmin

Results
Write an ETL function to read three data files
The function takes the Wikipedia JSON, the Kaggle metadata and MovieLens csv files and creates three separate DataFrames.

Extract and Transform the Wikipedia data
I filtered out the TV shows, consolidated the redundant data, removed the duplicates and formatted the Wikipedia data.

Extract and Transform the Kaggle and rating data
Again, I consolidated the redundant data, removed the duplicates, formatted and grouped the data.
The Kaggle and rating data were then merged with the Wikipedia movies DataFrame.

Summary
The ETL function created collects and cleans movie data from different sources (Wikipedia JSON and Kaggle and ratings csv files). It transforms and merges the data and loads it into two updatable PostgreSQL dataset tables ready to be used by the hackathon participants for their analysis.
