# Data Modeling with Apache Cassandra 

### Summary

A music streaming app, Sparkify wants to analyze the data on songs and user activity. The analytics team wants to know what songs users are listening to. Currently, there is no easy way to generate the results, since the data resides in a directory of CSV files on user activity on the app

We need to create an Apache Cassandra database with tables designed to handl queries on song play data to answer the questions. Also create a database schema and ETL pipeline for this analysis. Test the database and ETL pipeline by running queries from the analytics team.

### Project Description
Data Model with Apache Cassandra and build a complete ETL pipeline using Python. We will need to model the data by creating tables in Apache Cassandra to run queries, and complete the ETL pipeline that transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra using Python and SQL.

### Pre-Requisites
* Apache Cassandra
* Ensure cassandra (driver) is installed in a python3 environment
* Jupyter Notebook

### How to Run & Test

* Use Project_1B.ipynb (Jupyter Notebook) to Setup Database and Run ETL Pipeline. 
* Run all the cells of the notebook to verify the music database is setup correctly.
* Review the output of these cells to verify the queries produce desired results: 
** Query 1 Results:
** Query 2 Results:
** Query 3 Results:


### Files
| Filename |  |
| ------ | ------ |
| Project_1B.ipynb | Setup Database and Run ETL Pipeline |
| event_datafile_new.csv | Intermediate CSV file with relevant data aggregated from all event data files |
| images | Contains image file that shows how data is organized in the intermediate CSV file. |
| event_data | Contains songs & log data json files. |


### Acknowledgement
Author: Hari Raja
Framework: Udacity
Date: Apr 17 2020
