# Data Modelling with Apache Cassandra


## Overview

This project builds an ETL pipeline to create, fetch, and populate DB for the music streaming app Sparkify.
It uses Cassandra database with tables designed to optimize queries on song play analysis.

## Structure

The project contains the following elements:
* `Project_1B_ Project_Template.ipynb` defines the ETL pipeline
* `event_data/` contains events CSV files

## Schema
The schema ask the following questions:

- 1. Give me the artist, song title and song's length in the music app history that was heard during  sessionId = 338, and itemInSession  = 4
- 2. Give me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182
- 3. Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'