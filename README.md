# Data Modeling with Apache Cassandra
![image](images/cassandra.png)

## Motivation
This project is the hands-on project provided by udacity data engineering nanodegree. We have log file storing user activity and song data available for all the songs in Sparkify system. It is our job to extract, transform and load these data into Apache Cassandra database in order to satisfy our query demand.

## Introduction
We have the log file of November 2018 stored within event_data folder. Firstly, we convert the scattered files into one complete csv and then create customized tables in Cassandra according to our target query. Finally, we demonstrate the result with a pandas dataframe.

## Data Processing 
Below lists the detailed data processing procedure in this project

1. Converting multiple scattered files into one complete csv
2. Create cluster and session for Apache Cassandra
3. Create customized table and insert data from complete csv
4. Run select query to test the result of our target query
5. Convert results to pandas dataframe for better visualization

## Libraries Used
- pandas (dataframe and data processing)
- cassandra (to interact with Apache Cassandra)
- os (to interact with OS)

## Files and Folders
- event_data folder
    -> Original csv data files of November 2018 
- images
    -> Images used in Notebook or README
- Event_datafile_new.csv: The complete csv file of log data
- Data Modeling with Apache Cassandra.ipynb: Main notebook for the project

## Summary
We are able to perform ETL pipeline to load and convert data to our desired form. Furthermore, we successfully obtain the query result and visualize the result with pandas dataframe.

## Acknowledgement
Special thanks to udacity for providing required training, data source and resource to complete the project.
