# Customer-Viewership-segmentation-of-Netflix

The project aims to solve the problem of understanding the consumer best to be able to provide the right recommendations to increase viewership[ across shows/movies on netflix. To achieve this, the netflix dataset from kaggle was used containing information on close to 15.5K Netflix shows and movies consisting of 26 descriptive attributes such as rating, tags, genre, writer, director, actor etc.

Dataset : https://www.kaggle.com/datasets/ashishgup/netflix-rotten-tomatoes-metacritic-imdb

The goal is to provide a list of recommended movies/shows the user would enjoy based on their previous choices. To achieve this, Unsupervised Machine Learning techniques are used to cluster movies and shows to understand how they relate to each other in terms of ratings and their popularity.

The R programming Language is used to implement this project.

#### Methods

1. Preprocessing (ETL)
2. Visualization (EDA)
3. Dimensionality Reduction (PCA and t-SNE)
4. Clustering (Heirarchical, k-means)

#### Results

1. It is noted that categorical variables such as the writer who wrote the script, the genre of the content and language of production are highly indicative of the type of movies and shows tailored to engage the audience currently on Netflix. 
2. The PCA results indicate that the principal components from the continuous variables found have explained more than 85% of the variance noted in the data.
3. The modelling results noted from k-means and Heirarchical clustering showcases a clear logical separation among the different clusters specifically noted in the k-means clustering.
