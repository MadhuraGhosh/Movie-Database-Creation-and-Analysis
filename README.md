# Movie-Database-Creation-and-AnalysisMovie Database Creation and Analysis
This project demonstrates how to create a SQLite movie database with 500 entries, populate it with randomly generated data, and perform analysis using Python libraries such as Pandas, Matplotlib, and Seaborn.

Project Structure
Database Creation: A SQLite database (movies.db) is created and populated with 500 movies using the faker library for random data generation.
Data Analysis: The movie data is loaded into a Pandas DataFrame for analysis, including summary statistics, genre distribution, and average ratings by genre.
Visualization: Various visualizations (e.g., rating distribution, average rating by genre) are generated using Matplotlib and Seaborn.
Requirements
Before you begin, make sure you have the following Python libraries installed:

sqlite3: Built-in with Python.
pandas: For data manipulation and analysis.
faker: To generate fake data.
matplotlib: For creating visualizations.
seaborn: For enhanced data visualizations.
1. Create and Populate SQLite Database
The project starts by creating an SQLite database (movies.db) and a table movies. The table includes the following fields:

id: Movie ID (Primary Key).
title: The title of the movie.
genre: The genre of the movie (Action, Comedy, Drama, etc.).
director: The name of the director.
release_year: Year the movie was released.
duration: Movie duration in minutes.
rating: IMDb-style rating between 1.0 and 10.0.
votes: Number of votes the movie received.
Verify Database Creation
To check if the database and the movies table were created successfully.
Load Data into Pandas for Analysis
Basic Data Analysis
Perform basic analysis on the dataset, such as getting summary statistics, counting movies by genre, and finding the average rating per genre.
Data Visualization
Advanced Analysis (Optional)
This project demonstrates the full workflow of creating a SQLite database, populating it with random movie data, and performing data analysis using Python. The dataset can be further explored with additional analysis or machine learning techniques if desired.

