# Cinemaphile

### Project Description
I hand-entered data about my movie-watching habits, most of which was pulled from Netflix (they provide your viewing history in a CSV or Excel file). I was interested in different patterns, such as the average length of the movies I watched, the director(s), genre/subgenre, and relationships between this categories.

## Features from CodeLou Data Analysis 1 Project Requirements:
#

    1. Minimum of 5 Github commits

    2. Read in data from a local csv, excel file, json, or any other file type. 
    I am reading in from a CSV file.

    3. Use built-in pandas or numpy functions to do things like remove 0’s and null values where they don’t belong in your dataset. 
    I replaced null/missing values and removed incorrect data using fillna(), astype(), and replace().

    4. Use at least 5 different built-in Python functions to find out something about your data. 
    I used head(), isnull(), info(), len(), describe(), nunique(), and corr().

    5. Do 5 basic calculations with Pandas, like finding the sum(), median(), mean(), or mode() of a column. 
    I intend to find the total and the average runtime of all movies watched, the average rating of the movies, the year containing the most movies I watched, etc.

    6. Make 2 basic plots with matplotlib, seaborn, or any other kind of visualization library that you think looks interesting. 
    I made multiple plots -- including scatterplots and histograms.

    7. Write markdown cells in Jupyter explaining your thought process and code.

## How to run

#

1. python -m venv venv

2. venv/Scripts/activate

3. pip install -r requirements.txt

## Describe the data used in the analysis
#
The dataframe contains 9 columns and 959 rows. Each entry is a movie that I have watched in its entirety and other data to describe the movie. 

### What the headings mean:


Title - the movie's title

Year - the movie's release year

Runtime - the movie's length in hours and minutes

RT_Score - the movie's Rotten Tomatoes score

Genre - the movie's genre

Subgenre - the movie's subgenre

Rating - the age rating (if no MPA/MPAA rating available, "NR" or Not Rated is given. TV ratings such as TV-MA, TV-15, etc. were generally reported as R, PG-13, and so on, if the MPA/MPAA standards corresponded.)

Director - the movie's director(s)

Theatres - a boolean reporting whether or not I watched the movie when it was released in theatres