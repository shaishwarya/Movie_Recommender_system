# Movie_Recommender_system-
 This part is focused around building various kinds of recommendation engines; namely the Simple Generic Recommender, the Content Based Filter and the User Based Collaborative Filter. The performance of the systems are evaluated in both a qualitative and quantitative manner.
It is content based movie recommendation system, in this i have used two content based engines; one that took movie overview and taglines as input and the other which took metadata such as cast, crew, genre and keywords to come up with predictions using cosine similarity.
Cosine similarity-The cosine similarity measures the similarity between vector lists by calculating the cosine angle between the two vector lists. If you consider the cosine function, its value at 0 degrees is 1 and -1 at 180 degrees.
Approach
The problem was divided into several steps:

Data Collection: Data was collected from the MovieLens website and through a script that queried for data from various TMDB Endpoints.
Preprocessing : Make data ready according our purpose.
Model building: Using machine learning.
After this we will going convert this into website, after this we will going to deploy the website.
Recommendation Systems: Four different recommendation systems were built using various ideas and algorithms such as IMDB's Weighted Rating, Content Based Filtering and Collaborative Filtering.
Four recommendation engines were built based on different ideas and algorithms:

Simple Recommender: This system used overall TMDB Vote Count and Vote Averages to build Top Movies Charts, in general and for a specific genre. The IMDB Weighted Rating System was used to calculate ratings on which the sorting was finally performed.
Content Based Recommender: I built two content based engines; one that took movie overview and taglines as input and the other which took metadata such as cast, crew, genre and keywords to come up with predictions. I also devised a simple filter to give greater preference to movies with more votes and higher ratings.
Collaborative Filtering: I used the powerful Surprise Library to build a collaborative filter based on singular value decomposition. The RMSE obtained was less than 1 and the engine gave estimated ratings for a given user and movie.
Hybrid Engine: I brought together ideas from content and collaborative filtering to build an engine that gave movie suggestions to a particular user based on the estimated ratings that it had internally calculated for that user.

Software Require
Jupyter notebook
Pycharm
Heroku

Python libraries
Numpy
Pandas
ast
nltk
sklearn
pickle

Data set link-
 (link :https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

