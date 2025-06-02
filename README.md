# Task1
Task 1: Data Cleaning and Preprocessing

Netflix Data Analysis

Overview
This project explores and cleans a Netflix dataset (Netflix_Raw.csv) using Python and Pandas in Task1.ipynb. The dataset contains details about movies and TV shows, including titles, directors, countries, release years, ratings, and durations.

Dataset Columns
Show_Id: Unique ID
Type: Movie or TV Show
Title: Content title
Director: Director name
Country: Production country
Date_Added: Date added to Netflix
Release_Year: Release year
Rating: Content rating
Duration: Duration (minutes or seasons)

Notebook Steps
Load Data: Reads Netflix_Raw.csv.
Exploration: Shows first 10 rows, column names, missing values (1 in Title, 3 in Director, 1 in Country), duplicates (none), and unique values.
Cleaning: Fills missing Title, Director, and Country with "Unknown".
Save: Exports cleaned data to Cleaned_Netflix.csv.

Prerequisites
Python 3.x
Pandas (pip install pandas)
Google Colab

Output
Cleaned dataset saved as Cleaned_Netflix.csv.
