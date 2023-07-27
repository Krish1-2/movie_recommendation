# movie_recommendation
* created a movie recommendation system.
* Used the movie dataset from Kaggle
* have modified the dataset using pandas library to make it more efficient
* removed stop words and applied the stem function to remove repeatative words from the dataset 
* created a vector for each movie using ski-kit learn based on the frequency of a keywords appearing in the genres,cast,crew and desc.
* the vectors dimensions came out to be approximately (5k,5k)
* producing recommendations based on the cosine angle difference between movies
