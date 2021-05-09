# ETL - Extract, Transform, Load

## Overview

This project focused on the Extraction, Transformation, and Loading of data from multiple sources, in order to create a clean dataset for Amazing Prime's hackathon.

## Files

Below are descriptions of the files in this repository:

- ETL_function_test
  - First creation of a function to extract data from wikipedia-movies.json, ratings.csv, and movies_metadata.csv
- ETL_clean_wiki_movies
  - Updated the code to clean the wikipedia data 
- ETL_clean_kaggle_data
  - Updated the code to also clean the kaggle data (movies_metadata.csv) and ratings data
- ETL_create_database
  - Refactors the function to clean the data and import two datasets (a merged wikipedia/kaggle dataset and the ratings csv) to a SQL database
- Movies_Query.png and Ratings_Query.png
  - Images of the SQL queries with the row counts of the imported datasets
