# Movies-ETL

### Overview of Movies-ETL

The purpose of this project is to help "Amazing Prime" create an automated data pipeline that takes in new movie data (from wikipedia & Kaggle), performs appropriate transformation and loads the transformed data into a table on PostgreSQL. The project invoved;

  1. Writing and ETL function to read datafiles
  2. Extract and transform the wikipedia data
  3. Extract and transform the kaggle data
  4. Creating the movie database

To carryout the ETL, I utilized the following resources;

  - Data Source: movies_metadata, ratings.csv, wikipedia-movies.json
  - Softwares: Anaconda 4.8.3, Jupyter Notebook, Python 3.7.6 - Pandas, pgAdmin (PostgreSQL)