# Movie_Recommender_system-
 This part is focused around building various kinds of recommendation engines,known as the Content Based Filter and the User Based Collaborative Filter, user based Filter. The performance of the systems are evaluated in both a qualitative and quantitative manner.
I have made a content based movie recommendation system, in this i have used two content based engines.
The first one takes movie overview and taglines as input and the other one takes metadata such as cast, crew, genre and keywords to come up with predictions using cosine similarity.
The cosine similarity measures the similarity between vector lists by calculating the cosine angle between the two vector lists. If you consider the cosine function, its value at 0° is 1 and -1 at 180°.

**Approach -**
The problem was divided into several steps:

Data Collection: I have taken the dataset available at kaggle.

Preprocessing : For utilization of my purpose, i have preprocessed the dataset found.

 I have build model using machine learning libaries.
 
By using the prepared model i have created a website.

**Recommendation Systems: Four different recommendation systems were built using various ideas and algorithms such as IMDB's Weighted Rating, Content Based Filtering and Collaborative Filtering**.

Simple Recommender: This system used overall TMDB Vote Count and Vote Averages to build Top Movies Charts, in general and for a specific genre. The IMDB Weighted Rating System was used to calculate ratings on which the sorting was finally performed.

Content Based Recommender: I built two content based engines; one that took movie overview and taglines as input and the other which took metadata such as cast, crew, genre and keywords to come up with predictions. I also devised a simple filter to give greater preference to movies with more votes and higher ratings.

Collaborative Filtering: I used the powerful Surprise Library to build a collaborative filter based on singular value decomposition. The RMSE obtained was less than 1 and the engine gave estimated ratings for a given user and movie.

Hybrid Engine: I brought together ideas from content and collaborative filtering to build an engine that gave movie suggestions to a particular user based on the estimated ratings that it had internally calculated for that user.

**Software Required**
Jupyter notebook
Pycharm
Heroku

**Python libraries used-**
Numpy,
Pandas,
ast,
nltk,
sklearn,
pickle.

**Data set link-**
 (link :https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
 
