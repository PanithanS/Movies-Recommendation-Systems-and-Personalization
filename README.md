# Recommendation systems for the movie datasets
Recommendation systems are a specialized area of machine learning that focuses on the evaluation and management of users or items. These techniques are frequently used by big companies like Google, Instagram, Spotify, Amazon, and Netflix to increase user engagement and platform usage. For instance, Spotify uses recommendation algorithms to provide music that is similar to tracks that a user has previously liked or enjoyed in order to keep them using their music streaming service. Amazon, meanwhile, leverages recommendation algorithms to provide product recommendations to specific consumers based on the extensive user data they have collected.

# Contents
Here, we mock-up the movie recommendation system with data collected from IMDb. We build a machine learning-driven method for filtering and predicting the movie preferences of the user by analyzing their personal tastes and community ratings. This recommendation system facilitates movie selections for the user and guides them toward a specific domain of movies.

- Simple Recommender (IMBb dataset)
- Knowledge Recommender (IMBb dataset)
- Content-based Recommender (IMBb dataset)
- Metadata-based Recommender (IMBb dataset)

...more details are going to be added

# Datasets
- For IMDb dataset, we can download the necessary files from Kaggle: https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset
- For the MovieLens dataset, we can download from Kaggle: https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset

## About the IMBb dataset
These data contain metadata for all 45,000 movies listed in the Full MovieLens Dataset. Movies that were released on or before July 2017 are included in the dataset. Cast, crew, narrative keywords, budget, revenue, posters, release dates, language, production firms, nations, vote totals, and vote averages are just a few examples of the data points.

- Fig. The 'df.head()' gives an overlook for the IMBb dataset.
![image](https://github.com/PanithanS/Recommendation-Systems-IMDBs/assets/83627892/5131e7fe-d1fa-4761-8e9e-ed1c7c649ac2)

## About the MovieLens dataset
The MovieLens datasets, provided by the GroupLens Research Project at the University of Minnesota, consist of 100,000 ratings spanning from 1 to 5 for a total of 1682 films. These ratings were contributed by 943 users, each of whom rated at least 20 films. Additionally, user demographic information, including age, gender, occupation, and zip code, was collected through the MovieLens website (movielens.umn.edu) over a seven-month period, from September 19, 1997, to April 22, 1998. Data with fewer than 20 ratings or incomplete demographic details were excluded from the final dataset through a data-cleaning process.

# Acknowledgements
- This work was inspired by the book: "Hands-On Recommendation Systems with Python: Start building powerful and personalized, recommendation engines with Python"
- The Python codes were inspired by the original GitHub: https://github.com/PacktPublishing/Hands-On-Recommendation-Systems-with-Python
- The published work for the MovieLens dataset refers to 'Herlocker, J., Konstan, J., Borchers, A., Riedl, J.. An Algorithmic Framework for Performing Collaborative Filtering. Proceedings of the 1999 Conference on Research and Development in Information Retrieval. Aug. 1999.'
