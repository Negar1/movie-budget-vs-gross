# movie-budget-vs-gross
 
Extracted data after cleaning are provided as df_final_movie_imdb.csv. these data are 
used to check if there is a correlations between budget with IMDB score and worldwide gross
of movies and found there is no meaningful correlation between budget and IMDB or between budget and gross of movies overall. 


What are these data:
Purpose of this project is by having different types of data of movies and their IMDB scores,
one could predict the other movies IMDB scores. My plan is to check at least three methods of regression,
 decision trees and neural networks for it. Here I have extracted 5000 movie’s data such as 
(movie title, Release Date, Production Budget, its Domestic Gross and Worldwide Gross and its Movie Link) 
from https://www.the-numbers.com/movie/budgets/all. Each movie had a link for extra information such as its
 MPAA, duration, color, genre, keywords, language and company from https://www.the-numbers.com/movie. 
Further data such as IMDB score, director, crews are extracted from www.IMDB.com.
Data are cleaned considering: Finding and removing duplicated movies, check nulls for each features and do more
 study on each item to see if it can be possibly replaced by anything or need to be removed 
(for example missing language were replaced by language of other movies from same director), 
Check synonyms for example in MPAA or keywords and make them unique, hot encoding for genres, ratings, languages, countries, etc.
Final file is also provided in GitHub as df_final_movie_imdb.csv. 
Here I have checked the correlations between budget with IMDB score and worldwide gross 
of movies and found there is no meaningful correlation between budget and IMDB or between budget 
and gross of movies overall. Also effect of genres on IMDB scores are checked.
 