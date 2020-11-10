Description:
*******************************************************************

This is a team assignment with maximum size of 2. Individual assignments submissions are also permitted

********************************************************************

Overview and Assignment Goals:

The objectives of this assignment are the following:
Develop a Recommender System that Uses the Rating Information (Matrix) and Side-Information (i.e., Additional Content).
Think about using classification, clustering, or anything you learned this semester.
The Scoring Metric will be Root Mean Squared Error (RMSE) where the predictions are rating in the range 0-5. As such, you may want to switch to a regression setting since the output can be real-valued.

Detailed Description:

Recommender Systems are all pervasive. The objective of this movie recommender system is to predict the 5-star rating a movie will get for a given user. You can use content features as well as the rating matrix to make your final predictions.
Data Description:

As part of the training I provide you several different files all zipped together as additional_files.zip (Uploaded in the training portion of this assignment).

Once you unzip this file you will find a readme.txt with a listing of the files and useful information about them (replicated below).

* train.dat: This file contains the rating of a user for a given movie.

* test.dat: This file contains user movie pairs but no rating (Your goal is to predict these ratings for user-movie pairs)

* movie_genres.dat: This file contains the genres of the movies.

* movie_directors.dat: This file contains the directors of the movies. .

* movie_actors.dat: This file contains the main actors and actresses of the movies. A ranking is given to the actors of each movie according to the order in which they appear on the movie IMDb cast web page. .

* tags.dat: This file contains the set of tags available in the dataset. .

* user_taggedmovies.dat: These files contain the tag assignments of the movies provided by each particular user. .

* movie_tags.dat: This file contains the tags assigned to the movies, and the number of times the tags were assigned to each movie. .

test.dat: Test set consisting of user-movie pairs for which you need to produce the ratings

example_entry.dat: A sample submission with 71299 entries in the range of 0-5.
