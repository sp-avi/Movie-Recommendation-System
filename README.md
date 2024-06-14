# Movie Recommendation System

## Overview
This project aims to develop a movie recommendation system using machine learning techniques. The system will suggest movies based on user preferences and ratings.

## Algorithms
Content-Based Filtering: This method recommends movies based on their attributes, such as genres, actors, and directors. The system calculates the similarity between movies based on these attributes and recommends movies with the highest similarity scores.
Collaborative Filtering: This method recommends movies based on the preferences of similar users. The system builds a matrix of user ratings and calculates the similarity between users based on their ratings. It then recommends movies that are highly rated by similar users.

## Implementation
Python: The project is implemented using Python and the Pandas library for data manipulation.

## Functions
recommend_movies: This function takes a movie title and returns a table plot of the top 10 most similar movies based on popularity.
get_recommendations_new: This function takes a movie title and returns a table plot of the top 10 most similar movies based on popularity.
build_model: This function builds and trains the neural network model for the collaborative filtering algorithm.
train_model: This function trains the neural network model using the training data.

## Usage
Example Usage:
python
recommend_movies("Thor", nn_data, orig_data)
recommend_movies("Eternals", nn_data, orig_data)

## Conclusion
This project demonstrates how to create a movie recommendation system using machine learning techniques. The system can be extended to include more advanced features and algorithms to improve its accuracy and user experience.

## Future Work
Improve the accuracy of the recommendation models: This can be achieved by incorporating more features, such as user demographics and movie reviews.
Expand the dataset: The system can be expanded to include more movies and users to improve its accuracy and coverage.
Implement a user interface: A user interface can be implemented to allow users to input their preferences and view the recommended movies.
