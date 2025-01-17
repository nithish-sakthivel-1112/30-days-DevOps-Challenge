## The NBA Data Lake
Welcome to the NBA Data Lake store! This project contains the setup_nba_data_lake.py script, which is designed to automate the creation of a data lake for NBA analytics using AWS services. Combining Amazon S3, AWS Glue, and Amazon Athena, the script sets up the infrastructure necessary to efficiently collect, manage, and query NBA-related data

consider
The setup_nba_data_lake.py script facilitates the following procedures.

## Amazon S3 integration
  1) Creates an S3 bucket to store both raw and processed NBA data.
  2)Uploads NBA data samples in JSON format to the S3 bucket.
  3)AWS glue system

## Glue is the database that will compose the data lake.
  1)Set up an external table in Glue for easy data querying.

## Amazon Athena system

  Athena configures it to query data directly from the S3 bucket, enabling faster and more efficient data analysis.
  This repository provides an easy way to build robust data lakes for NBA analytics, for data feeds, scheduling, and queries that AWS services facilitate
