# Extract-Transform-Load Movie Data

## Project Overview
The purpose of this project is to create a function that receives three files and performs the ETL process, adding the data to a PostgreSQL database in two tables. The data is pulled from two csv files: Kaggle Metadata and MovieLens rating data, and a json file of Wikipedia movie data. The data is transfomed and merged into a dataframe showing metadata and rating data and loaded into two updatable tables to be analyzed in a hackathon.

## Resources
Data Sources: movies_metadata.csv, ratings.csv, wikipedia-movies.json
Software: Python 3.7.6, Pandas 1.3.4, Jupyter Notebook 6.4.5, PostresSQL 11, pgAdmin 4
