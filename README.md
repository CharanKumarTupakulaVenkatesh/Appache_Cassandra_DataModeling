# Project: Data Modeling with Apache Cassandra

## Project: Data Modeling with Cassandra

To create an Apache Cassandra database which can create queries on song play data to answer the questions, and wish to bring you on the project. Your role is to create a database for this analysis. we will be able to test database by running queries given to us by the analytics team from Sparkify to create the results.

## Project Overview
In this project, we will create on data modeling with Apache Cassandra and complete an ETL pipeline using Python. To complete the project, we will need to model our own  data by creating tables in Apache Cassandra to run queries. we are provided with part of the ETL pipeline that transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables.

We have provided you with a project template that takes care of all the imports and provides a structure for ETL pipeline we woul'd need to process this data.
## Project Details

## Datasets
For this project, we ll be working with one **dataset: event_data**. The directory of CSV files partitioned by date. Here are examples of filepaths to two files in the >dataset:
>
 >-event_data/2018-11-08-events.csv
 >-event_data/2018-11-09-events.csv
 >
## Project Template

> The project template includes one Jupyter Notebook file, in which:
> 
>
>-we will process the **event_datafile_new.csv** dataset to create a denormalized dataset
>
>-we will model the data tables keeping in mind the queries we need to run
>
>-we have been provided queries that we will need to model your data tables for
>
>we will load the data into tables we create in Apache Cassandra and run your queries
## Project Steps
Below are steps you can follow to complete each component of this project.

**Modeling your NoSQL database or Apache Cassandra database**
>1.Design tables to answer the queries outlined in the project template
>2.Write Apache Cassandra CREATE KEYSPACE and SET KEYSPACE statements
>3.Develop your CREATE statement for each of the tables to address each question
>4.Load the data with INSERT statement for each of the tables
>4Include IF NOT EXISTS clauses in your CREATE statements to create tables only if the tables do not already exist. We recommend you also include DROP TABLE statement for each table, this way we can run drop and create tables whenever we want to reset our database and test our ETL pipeline
>5.Test by running the proper select statements with the correct WHERE clause
>6.Build ETL Pipeline
>7.Implement the logic in section Part I of the notebook template to iterate through each **event file** in **event_data** to process and create a new CSV file in Python
>8.Make necessary edits to Part II of the notebook template to include Apache Cassandra CREATE and INSERT statements to load processed records into relevant tables in your data model
>9.Test by running SELECT statements after running the queries on your database


