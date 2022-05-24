# Movie-Analysis

![alt text](image/poster.png "Poster")

## Information
This project uses Python Pandas, Numpy & Matplotlib to analyze and answer questions about a movie dataset from IMDb (Internet Movie Database). The dataset contains 100 years worth of movies (from 1916-2016).

The data is broken down by title, genre, budget, revenue, rating, etc. Since it is a bit messy, I start by cleaning it. This involves:

* Removing rows that will not be needed in analysis
* Changing the data types of certain columns
* Renaming some columns
* Filter wanted data from unwanted data in certain Series in the DataFrames

The next step is to conduct Explorartory Data Analysis. This gives me a rough overview of the data I am working with and enables me to answer questions such as:

* What are the top ten movie production companies in USA with regards to profitablility?
* Does the budget of a movie affect it's rating/ popularity?
* Which movie genres are the most profitable? 
* Is the most popular genre the most profitable?
* What is the best month to release a movie with regards to revenue generated?
* Is the movie industry becoming more or less profitable in USA?

## Acknowledgements
This data was gotten from Kaggle. If you are interested in doing analysis on the same dataset, you can find it [here](https://www.kaggle.com/danielgrijalvas/movies).