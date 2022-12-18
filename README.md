# Movie-Recommendation-System



<!-- Add banner here -->

# Project Summary

 A Recommendation System is a filtration program whose prime goal is to predict the “rating” or “preference” of a user 
 towards a domain-specific item or item. In our case, this domain-specific item is a movie, therefore the main focus of our 
 recommendation system is to filter and predict only those movies which a user would prefer given some data about the user him or herself.


The Objective of the Project is to create a Content Based Recommender System strategy is based on the data provided about the items. The algorithm 
recommends products that are similar to the ones that a user has liked in the past. This similarity (generally cosine similarity) is computed from 
the data we have about the items as well as the user’s past preferences.
For example, if a user likes movies such as ‘The Prestige’ then we can recommend him the movies of ‘Christian Bale’ or movies 
with the genre ‘Thriller’ or maybe even movies directed by ‘Christopher Nolan’.So what happens here the recommendation system checks 
the past preferences of the user and find the film “The Prestige”, then tries to find similar movies to that using the information 
available in the database such as the lead actors, 
the director, genre of the film, production house, etc and based on this information find movies similar to “The Prestige”. 

**Cosine similarity** in the recommendation system is used with the same principle of cosine angles, where even 
 if the similarity of the content is less similar it would be considered as the least recommended content, and for 
 higher similarity of contents, the recommendations generated would be at the top. Cosine similarity is also used
 in textual data to find the similarity between the vectorized texts from the original text document.

<!-- Describe your project in brief -->

# Dataset Used

The dataset for the data analysis can be obtained via [kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata). 


# Deployment/Demo

The project is live/deployed on Streamlit and can be accessed via this [link](https://sumit6037-movie-recommendation-system-app-mix5a1.streamlit.app/)

