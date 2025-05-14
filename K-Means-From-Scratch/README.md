
# Unsupervised learning and Recommender System

A brief description of what this project does and who it's for

- **Algorithmic Analysis K-Means Clustering with Real World Dataset**

Download a simulated dataset: kmeans_data.zip from Modules->Datasets. Then,
implement the K-means algorithm from scratch. K-means algorithm computes the distance of a
given data point pair. Replace the distance computation function with Euclidean distance, 1-
Cosine similarity, and 1 – the Generalized Jarcard similarity (refer to:
https://www.itl.nist.gov/div898/software/dataplot/refman2/auxillar/jaccard.htm).

-  Run K-means clustering with Euclidean, Cosine and Jarcard similarity.

- Compare the accuracies of Euclidean-K-means Cosine-K-means, Jarcard-K-means.

- Set up the same stop criteria: “when there is no change in centroid position OR when the SSE value increases in the next iteration OR when the maximum preset value

-  Compare the SSEs of Euclidean-K-means Cosine-K-means, Jarcard-K-means with respect to the following three terminating conditions: 
    - when there is no change in centroid position
    - when the SSE value increases in the next iteration
    - when the maximum preset value (e.g., 100) of iteration is complete

----
**Machine Learning with Matrix Data for Recommender Systems**
Recommender systems are a hot topic. Recommendation systems can be formulated as a
task of matrix completion in machine learning. Recommender systems aim to predict the
rating that a user will give for an item (e.g., a restaurant, a movie, a product).

Download the movie rating dataset from: https://www.kaggle.com/rounakbanik/themovies-dataset. These files contain metadata for all 45,000 movies listed in the Full
MovieLens Dataset. The dataset consists of movies released on or before July 2017. Data
points include cast, crew, plot keywords, budget, revenue, posters, release dates, languages,
production companies, countries, TMDB vote counts and vote averages. This dataset also
has files containing 26 million ratings from 270,000 users for all 45,000 movies. Ratings are
on a scale of 1-5 and have been obtained from the official GroupLens website. 