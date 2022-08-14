# Movies-ETL: Module 8 Challenge

## Overview of Project

### Background and Purpose

Amazing Prime Video is a platform for streaming movies and TV shows on Amazing Prime, the world's largest online retailer. The Amazing Prime Video team would like to develop an algorithm to predict which low budget movies being released will become popular, so that they can buy the streaming rights at a bargain. To inspire the team, and have some fun, and connect with the local coding community, Amazing Prime has decided to sponsor a hack-a-thon, providing a clean dataset of the movie data and asking the participants to predict the popular pictures. Britta, a member of the Amazing Prime Video team, has been tasked with creating the datasets for the hack-a-thon. There are two data sources: a scraping of Wikipedia for all movies released since 1990, and rating data from Movielen's website. Britta needs help extracting the data from the two sources, transforming it into one clean dataset, and loading the dataset into a SQL table.

### Resources

- Data Sources: movies_metadata.csv, ratings.csv, wikipedia-movies.json
- Software: Anaconda 4.13, Jupyter Notebook, PgAdmin4 6.8,  Python 3.7.13, Visual Studio Code 1.68.1

## Deliverables

+ Deliverable 1: Write an ETL function to read three data files
  - Lessons reviewed:
    * Load and extract the Wikipedia data
    * Extract the Kaggle data
+ Deliverable 2: Extract and Transform the Wikipedia Data
  - Lessons reviewed:
    * Clean and filter data with list comprehensions
    * Write functions
    * Create the clean movie function
    * Remove duplicates with regular expressions
    * Remove columns with null values
    * Drop null values and convert data to string values
    * Clean the box office data
    * Clean the budget data, the release date, and the running time
+ Deliverable 3: Extract and Transform the Kaggle Data
  - Lessons reviewed:
    * Clean the budget data, the release date, and the running time
    * Clean the Kaggle data
    * Merge Wikipedia and Kaggle DataFrames
    * Transform and merge the ratings data 
+ Deliverable 4: Create the Movie Database
  - Lessons reviewed:
    * Create and connect to the database, then import data
