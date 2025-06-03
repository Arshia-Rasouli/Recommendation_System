# Content-Based Movie Recommender System

This Project  implements a basic **Content-Based Movie Recommender System**. This system recommends movies by analyzing the characteristics (content) of movies the user has previously liked and suggests similar items.

## About Content-Based Filtering

Content-based filtering works by building a profile of the user's interests based on the features of items they have consumed (e.g., rated movies highly). It then recommends new items that have similar features to the items in the user's profile. In this project, movie genres are used as the primary content features to define both movie characteristics and user preferences.

## Key Steps Involved

* **Data Loading and Preprocessing**: Loading datasets and cleaning movie titles and genres.
* **Genre Feature Matrix Creation**: Transforming genre information into a numerical representation.
* **Target User Profile Construction**: Defining user's input and building their preference profile.
* **User's Weighted Genre Profile Calculation**: Determining the user's weighted preferences for various genres.
* **Recommendation Generation and Ranking**: Calculating similarity scores between movies and the user's profile, and sorting them.
* **Displaying Top Recommendations**: Presenting the final list of recommended movies.

