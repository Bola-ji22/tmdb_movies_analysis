# (tmdb_movie_analysis)
## by (Oladapo Bolaji Tosin)


## Dataset

> The "Tmdb" dataset provides information on Hollywood movies created from the year 1960 to 2015. The purpose of the dataset is to investigate the factors that dirve the popularity of a movie. The dataset includes information on various attributes such as id, imdb_id, popularity, budget, revenue , original_title, cast, homepage, director, tagline, keywords, overview, runtime, genres, production_companies, vote_count, vote_average, release_year, budget_adj, revenue_adj. With a total of 10866 observations and 11 variables, the data provides insights into the . By analyzing variables such as user type, member gender, and age group, one can determine which demographic segments are most likely to participate in the bike sharing system. The data also provides information on trip duration, start and end time, and day of the week, which can be used to analyze usage patterns and identify peak usage times.

## Summary of Findings

1. The highest number of high budget movie created in a year was in 2010, with a record 31 high budget movie and there was an unprecedented raise in the number of high budget movies from 1997 to 2015.

2. It was found out the **Michael Bay** has directed the most high budget movies and he also has the highest cumulative budget over those movies.

<u>The top 10 director by Number of high budget movies directed</u>

- Michael Bay	    -    9
- Ridley Scott	    -    8
- Roland Emmerich	-    7
- Steven Spielberg  -    7
- Peter Jackson	    -    6
- Robert Zemeckis	-    6
- Ron Howard	    -    6
- Tim Burton	    -    6
- Christopher Nolan	-    5
- Francis Lawrence  -    5

<u>The top 10 director by Cumulative budget over movies</u>


- Michael Bay	    -  \$1,451,406,867
- Peter Jackson		-  \$1,158,797,315
- Ridley Scott	    -  \$1,053,604,050
- Roland Emmerich	-  \$1,011,792,160
- Steven Spielberg	-  \$924,808,989
- Christopher Nolan	-  \$904,266,114
- Tim Burton		-  \$888,322,172
- Robert Zemeckis	-  \$885,692,880
- Ron Howard  	    -  \$779,446,169
- Francis Lawrence	-  \$653,427,268

With this information the average budget of each directed movie can be calculated per director.

3. It was observed that **Comedy** has been the most popular genre in the past *10 years*, Coming up top **8** times in the the last 10 years. The comedy genre peak it highest number of movies in the year 2014 with 140 comedy movies created that year.


## Limitation

The genres column contains entries for each row that are separated by a pipe(|) which makes it difficult to work with, so i had to assume the first genre for each row is the predominate one.
