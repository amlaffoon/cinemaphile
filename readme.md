# Cinemaphile

### Project Description
I hand-entered data about my movie-watching habits, most of which was pulled from Netflix (they provide your viewing history in a CSV or Excel file). I was interested in different patterns, such as the average length of the movies I watched, the director(s), genre/subgenre, and relationships between these categories.

Along with some basic analysis of this data, I created a decision tree classifier that predicts whether or not I would watch a movie when it's released in theaters, based on my past viewing history. It was trained on the movies in the dataframe released in the year 2000 and onwards, since I could reasonable assume I was old enough to have gone to a movie theater then. Movies before that time were excluded so as not to skew the results.

I included a Boolean column that indicated whether I had seen the movie in theaters (True) or not (False) to use as the "target" for the decision tree. The other columns were the "features". [W3Schools, Decision Tree](https://www.w3schools.com/python/python_ml_decision_tree.asp)


## Features from CodeLou Data Analysis 1 Project Requirements:
#


    1. Minimum of 5 commits

    2. Read in data from a local CSV

    3. Use built-in pandas/numpy functions to remove 0/null values
    I used fillna(), astype(), and replace().

    4. use at least 5 different built-in functions to find out something about your data.
    I used head(), isnull(), info(), len(), describe(), nunique(), and corr().

    5. Do 5 basic calculations
    I used mean(), mode(), and sum().

    6. Make 2 basic plots/visualizations
    I made multiple plots -- including scatterplots and histograms.

    7. Write custom functions to operate on your data

    8. Write markdown to explain your thought process and code

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


### Things to revisit:
-I've added new movies to my "database" that I'd like to add in this project

-Learn how to use additional criteria to make a recommendation engine for myself

-Find more patterns in the data to determine how I choose movies and why I like them

-Create SQL database and an interface for easily updating the db with new movies over time
