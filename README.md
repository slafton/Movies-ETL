# Movies-ETL

## Project Overview
### In this project we constructed an ETL pipeline to deliver a comprehensive merged dataset of movies data for the Hackathon. We will take in the provided Wikipedia data, Kaggle metadata and MovieLens rating data and perform the appropriate transformations. We will then load the data into an existing PostgreSQL database.

## Resources
### Data Source: wikipedia-movies.json, movies_metadata.csv, ratings.csv
### Software: Python, Conda, Jupyter Notebook, PostgreSQL, pgAdmin

## Results
### 1. We wrote an ETL function to read in the files m and create DataFrames.
### 2. We filtered out TV shows, consolidated redundant data, removed duplicates and formatted the Wikipedia data.
### 3. Next we cleaned the Kaggle and ratings data and then merged it with the Wikipedia movies DataFrame.
### 4. Lastly we loaded the data to a PostgreSQL Movie Database.

### The following shows a sample of the movies table.
### ![image](https://github.com/slafton/Movies-ETL/blob/main/Screenshot%202022-08-23%20214813.png)
