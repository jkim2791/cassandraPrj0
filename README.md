# Data Modeling with Cassandra
This project models data by creating tables in Apache Cassandra to run queries. 


### Dataset
For this project, working with one dataset: `event_data`
The directory of CSV files partitioned by date. Here are examples of filepaths to two files in the dataset:
~~~
event_data/2018-11-08-events.csv
event_data/2018-11-09-events.csv
~~~

### Modeling Apache Cassandra database
1. Design tables to answer the queries outlined in the project template
2. Write Apache Cassandra `CREATE KEYSPACE` and `SET KEYSPACE` statements
3. Develop `CREATE` statement for each of the tables to address each question
4. Load the data with `INSERT` statement for each of the tables
5. Include `IF NOT EXISTS` clauses in `CREATE` statements to create tables only if the tables do not already exist.  
6. Test by running the proper select statements with the correct WHERE clause


### Build ETL Pipeline
1. Implement the logic in section Part I of the notebook template to iterate through each event file in `event_data` to process and create a new CSV file in Python
2. Make necessary edits to Part II of the notebook template to include Apache Cassandra `CREATE` and `INSERT` statements to load processed records into relevant tables in data model
3. Test by running `SELECT` statements after running the queries on your database
 
  `Project_1B_ Project_Template.ipynb`  is the main workspace.
