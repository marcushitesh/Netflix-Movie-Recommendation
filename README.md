Netflix Movie Recommendation System
This repository contains code for a Netflix movie recommendation system based on two different approaches: K-Prototype clustering and Cosine Similarity.

Description
The recommendation system is built using Python and leverages the kprototype algorithm for clustering and cosine similarity for movie recommendation. The model is deployed using Streamlit, providing two different approaches for movie recommendations.

K-Prototype Clustering Approach
In this approach, movies are clustered using the K-Prototype algorithm based on their features such as genre, release year, and other relevant attributes. Users are then recommended movies based on the cluster they belong to.

Cosine Similarity Approach
In the cosine similarity approach, movies are recommended to users based on the similarity of their features to those of other movies. This method calculates the cosine similarity between the features of movies and recommends movies with the highest similarity to those the user has previously interacted with or rated.
