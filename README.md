# Investigate A Dataset
## Udacity Financial Analyst Nanodegree Project 1

## Introduction
This project will provide an analysis of the movies data from TMDB. I will analyse the data to determine the attributes that are associated with popular movies. I will also perform data cleaning operations to extract the information that is relevant to my project. I will also plot visualizations to illustrate my findings better and in the end I will provide a conclusion of my findings.

## Data Overview
The TMDB movie database contains information about over 10000 movies and the attributes of each movie are-: id, imdb_id, popularity, budget, revenue, original_title, cast, homepage, director, tagline, keywords, overview, runtime, genres, production_companies, release_date, vote_count, vote_average, release_year, budget_adj, revenue_adj.

## Questions asked in this project
The type of question I would like to ask from this dataset include-:

1. What is the relation betwen the revenue and vote average?
1. Which movie has the longest runtime in the data set?
1. Which movie has the shortest runtime in the data set?
1. Which runtime range has the most sold copies of movies?
1. Do movies with higher expenditures also receive higher user rating?


## Data cleaning procedures taken
1. Dropping duplicate rows.
1. Dropping all the rows with missing values and zero values.

## Conclusion
In this project, I was able to analyze the movie dataset, by assising the qualities, attributes and properties that are associated with movies provided. After gathering the data, I went on to clean and trim the dataset by removing zero and duplicated values and other columns which were irrelevant to my research questions.

Then I answered the few of the questions I had, using pandas. I also plotted a few charts to visualize the results. The main attribute I used in the plots was vote_average. In those visualization I discovered that-: a. movies where higher costs were incurred are also rated high by users, b. movies that are highly rated by viewers have more revenue than their counterparts.

## Limitations
* There were many rows with columns with zero values which I dropped which casued me to loose 50% of the dataset. This means that the results I came up may not fully represent the whole dataset. If all values were thee it would have been more accurate.
* This dataset is not really an adequate representation of the movies industry since there are many movies which were released from other countries which doesnt appear in the dataset.

## References
1. [How to add a new column to an existing DataFrame?](https://stackoverflow.com/questions/12555323/how-to-add-a-new-column-to-an-existing-dataframe?rq=1)
1. [How do I get the row count of a Pandas DataFrame?](https://stackoverflow.com/questions/15943769/how-do-i-get-the-row-count-of-a-pandas-dataframe?rq=1)
1. [How do I select rows from a DataFrame based on column values?](https://stackoverflow.com/questions/17071871/how-do-i-select-rows-from-a-dataframe-based-on-column-values?rq=1)