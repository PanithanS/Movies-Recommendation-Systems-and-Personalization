# Recommendation systems
Recommendation systems are a specialized area of machine learning that focuses on the evaluation and management of users or items. These techniques are frequently used by big companies like Google, Instagram, Spotify, Amazon, and Netflix to increase user engagement and platform usage. For instance, Spotify uses recommendation algorithms to provide music that is similar to tracks that a user has previously liked or enjoyed to keep them using their music streaming service. Amazon, meanwhile, leverages recommendation algorithms to provide product recommendations to specific consumers based on the extensive user data they have collected.

# Example case for movie recommendation systems
- Fig: Here is an example that you may be familiar with. The first time that we created an account on Netflix, the system asked for use preference for movies.
![image](https://github.com/PanithanS/Movies-Recommendation-Systems/assets/83627892/943f0bf8-d7a9-4ee9-98fd-b526cc7ba440)

- Fig: Later, Netflix managed to recommend movies to users from different approaches and keep up-to-date relevant to use behaviors.
![image](https://github.com/PanithanS/Movies-Recommendation-Systems/assets/83627892/b488daff-5136-470b-ba22-0611ff1500b1)

# Contents
Here, we mock-up the movie recommendation system with data collected from IMDb. We build a machine learning-driven method for filtering and predicting the movie preferences of the user by analyzing their personal tastes and community ratings. This recommendation system facilitates movie selections for the user and guides them toward a specific domain of movies.

- **Simple Recommender(IMDb dataset)**
Simple recommenders are typically straightforward systems that offer recommendations based on general popularity or trends within a dataset. For the IMBb dataset, a basic recommender might suggest movies based on overall user ratings or the number of user reviews. It doesn't take into account the individual preferences or characteristics of the user.

- **Knowledge Recommender(IMDb dataset)**
Knowledge recommenders go beyond basic popularity metrics. They consider additional information about movies, such as genre, director, and actors. For the IMBb dataset, a knowledge-based recommender might suggest movies based on a user's past viewing history and their preferences for specific genres or actors.

- **Content-based Recommender(IMDb dataset)**
Content-based recommenders focus on the content of the items being recommended and the user's profile. In the context of the IMBb dataset, this system would recommend movies based on the attributes of the movies and the user's past interactions. For example, if a user has shown a preference for action movies, the content-based recommender would suggest other action movies.

- **Metadata-based Recommender(IMDb dataset)**
Metadata-based recommenders are similar to content-based systems but rely more on the metadata associated with the items. In the IMBb dataset, this might involve recommending movies based on specific metadata like release year, keywords, or themes.

- **Collaborative filtering Recommender(MovieLens dataset)**
Collaborative filtering is considered an advanced recommender system because it relies on user interaction data to make recommendations. It can be based on user-user collaborative filtering or item-item collaborative filtering. In the context of the MovieLens dataset, user-user collaborative filtering would recommend movies to a user based on the preferences of users with similar viewing habits. Item-item collaborative filtering would recommend movies that are similar to ones the user has already rated positively.

# Datasets
- For IMDb dataset, we can download the necessary files from Kaggle: https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset
- For the MovieLens dataset, we can download it from Kaggle: https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset

## About the IMBb dataset
These data contain metadata for all 45,000 movies listed in the Full MovieLens Dataset. Movies that were released on or before July 2017 are included in the dataset. Cast, crew, narrative keywords, budget, revenue, posters, release dates, language, production firms, nations, vote totals, and vote averages are just a few examples of the data points.

- Fig: The 'df.head()' gives an overlook for the IMBb dataset.
![image](https://github.com/PanithanS/Recommendation-Systems-IMDBs/assets/83627892/5131e7fe-d1fa-4761-8e9e-ed1c7c649ac2)

## About the MovieLens dataset
The MovieLens datasets, provided by the GroupLens Research Project at the University of Minnesota, consist of 100,000 ratings spanning from 1 to 5 for a total of 1682 films. These ratings were contributed by 943 users, each of whom rated at least 20 films. Additionally, user demographic information, including age, gender, occupation, and zip code, was collected through the MovieLens website (movielens.umn.edu) over seven months, from September 19, 1997, to April 22, 1998. Data with fewer than 20 ratings or incomplete demographic details were excluded from the final dataset through a data-cleaning process.

# Acknowledgements
- This work was inspired by the book: "Hands-On Recommendation Systems with Python: Start building powerful and personalized, recommendation engines with Python"
- The Python codes were inspired by the original GitHub: https://github.com/PacktPublishing/Hands-On-Recommendation-Systems-with-Python
- The published work for the MovieLens dataset refers to 'Herlocker, J., Konstan, J., Borchers, A., Riedl, J.. An Algorithmic Framework for Performing Collaborative Filtering. Proceedings of the 1999 Conference on Research and Development in Information Retrieval. Aug. 1999.'
