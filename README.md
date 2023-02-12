# Movie-recommendation-model

we all know that watching movies is lot fun. we all watched a many movies on different platform like Netflix. I have been thinking about how movie based platforms like Netflix or even on medium suggest anything based on user interest. how there recommendations are working based on the our interest.

A Recommender system, or a recommendation system, is a subclass of information filtering system that seeks to predict the “rating” or “preference” a user would give to an item.

simply, Recommender systems aim to predict users’ interests and recommend product items that quite likely are interesting for them.

# value of recommendation

## Netflix: 2/3 of movies watched are recommended

# Google news: recommendation generates 38% clickthrough

# Amazon: 35% sales from recommendation

So, as per the business standpoint, the more relevant products a user finds on the platform, the higher their engagement. it results in increased revenue for the various platform.

# Types of Recommendation system
Typically, machine learning algorithms are fit into two categories of the recommendation system.

1. Content-Based Recommendation Systems
2. Collaborative Filtering Recommendation Systems

# Content-Based Filtering
suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person likes a particular item, he or she will also like an item that is similar to it. ex. YouTube

# Collaborative Filtering
these systems are widely used, and they try to predict the rating or preference that a user would give an item-based on past ratings and preferences of other users. Collaborative filters do not require item metadata like its content-based counterparts.

Although, modern recommendation uses the both approaches called as Hybrid recommendation.
# Hybrid Engine
We brought together ideas from content and collaborative filtering to build an engine that gave movie suggestions to a particular user based on the estimated ratings that it had internally calculated for that user.

here are two categories of CF:

# User-based: 
  measure the similarity between target users and other users
# Item-based: 
  measure the similarity between the items that target users rates/ interacts with and other items
The key idea behind CF is that similar users share the same interest and that similar items are liked by a user. examples of this are found in the recommendation systems of Netflix, and Spotify.

Here, I have used a tmdb_5000_dataset. which contains nearly 5000 movies with their title, names, genres, cast etc. information.

we use pandas and numpy for the data preprocessing and sklearn for our machine Learning task.


in this project  We  built a movie recommendation system that considers user-user similarity, movie-movie similarity, global averages, and matrix factorization. These concepts can be applied to any other user-item interactions systems.
