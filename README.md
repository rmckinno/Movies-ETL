# Movies-ETL
Using ETL to Collect, Import, and Process Data

## Overview
Python and Pandas are used to import datasets from Wikipedia and Kaggle to create datasets for analysis that are then stored in PostgresSQL database. Creating two large datasets for movies released since the 1990s is the goal of this process. Following the ETL process, Wikipedia and Kaggle data were extracted into one json and two csv files and read using Python. They were transformed by cleaning and then joining them together. Finally, the combined datasets were loaded into a SQL database for future analytical use. 

## Resources
**Data Sources:** movies_metadata.csv (detailed movie data from Kaggle), ratings.csv (movie ratings data from MovieLens via Kaggle) , wikipedia-movies.json (detailed movie data from Wiki)

**Software:** VS Code 1.61, Jupyter Notebook 6.3, PostgresSQL 11.13, pgAdmin 5
