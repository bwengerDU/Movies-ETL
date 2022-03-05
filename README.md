# movies-ETL

## Overview

In this challenge I am helping a friend, Britta, to prepare for a hackathon event. Data was gathered from Kaggle and Wikipedia, combined, and then saved to a SQL database. This was accomplished by using the ETL process in which the data was Extracted, datasets were Transformed when cleaned and joined together, and the cleaned data was Loaded into a SQL database. The Wikipedia data was a JSON file containing a list of movies from 1990-2018. This file was loaded into the Pandas Dataframe in order to be cleaned and formatted correctly. Movie ratings came from a Kaggle file that was cleaned and formatted in order to be merged with the Wikipedia data. In order to make the merged data accessible for the hackathonthe data from Pandas was converted into a PostgreSQL database. This was accomplished by first creating a database via PG Admin4. 
