# Database Setup and Population Guide

**Welcome to the Database Setup and Population Guide for this repository.** This README provides a step-by-step guide on preparing your database schema, populating the database using CSV files, and executing SQL scripts for data manipulation and query execution. Whether you're setting up a new database or managing existing data, this guide will help you navigate the process smoothly.

## Getting Started

Before you begin, ensure you have PostgreSQL installed and running on your system. You'll also need access to psql, PostgreSQL's interactive terminal, and your CSV files ready for data import.

## Step 1: Preparing the Database Schema

### Creating the Database Schema

1. **Schema Definition**: The `schema.sql` file contains Data Definition Language (DDL) commands to define the structure of your database. This includes creating tables, views, and other necessary database objects.

2. **Execution**: To apply the schema to your database, run the following command in the psql terminal:
    ```
    \i schema.sql
    ```
   This command executes the SQL statements in `schema.sql`, setting up your database schema.

## Step 2: Populating the Database


### Running Population Scripts

- The `g1popu.sql` script containstables from the orginal dataset but are much more condense and easier to read.

- To execute this script, run the following command in the psql terminal:
    ```
    \i g1popu.sql
    ```

## Step 3: Running the application

### Running Applicaiton Steps

- in our directory, we are going to type
  ```
    \python app.py
    ```
- Now we should have the application running with our user friendly GUI

## GUI

- The GUI is set up to be very simple, our queries are listed below in which could be acceseed by just a click as shown below.

### Homepage
  
![V1](https://github.com/TCNJ-degoodj/project-group01/assets/122068476/47ad5d9d-d252-4f06-9e39-46431b36e94e)

### Example query page: Dam's who's had a baby over the size of 8 lbs.

![v2](https://github.com/TCNJ-degoodj/project-group01/assets/122068476/bfaf74ba-f00f-4456-8481-dd9b73fb4601)
