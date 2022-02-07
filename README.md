# Movies ETL

## Overview of the analysis

This project is dedicated to learn and practice the data pipeline ETL process, or Extract, Transform and Load, the process of moving information between databases.
For Movies ETL it was a task to create clean datasets from two sources - a scape of Wikipedia for all movies released since 1990, and rating data from the MovieLens website. 
Python and Pandas were used to perform data reading, cleaning, transforming into one dataset, and PostgreSQL was used to store finished data.

## Results

Since Amazing Prime company wanted to keep the final dataset updated on a daily basis, an automated pipeline was created that takes in new data, performs the appropriate transformations, and loads the data into existing tables. As a result, we got a refactored code with created functions that take in the three files — Wikipedia data, Kaggle metadata, and the MovieLens rating data — and perform the ETL process by adding the data to a PostgreSQL database.

## Summary

Functions were successfully tested and used in Jupyter Notebook. The data was cleaned using regular expressions - strings of characters that are used as a search pattern.
Finished dataset was imported to a PostgreSQL.