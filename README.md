# NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING


![Netflix_00](https://user-images.githubusercontent.com/98747222/233456891-3fd94248-a3e5-44c4-a70a-e7efc0475990.jpg)


To ensure an optimal user experience and prevent subscriber churn, it is essential for Netflix, the world's leading online streaming service provider with over 220 million subscribers as of 2022, to effectively cluster the shows on their platform..

Table of Content
Problem Statement
Objective
Dataset
Data Pipeline
Project Structure
Conclusion
Problem Statement
The goal of this project is to analyze the Netflix catalog of movies and TV shows, which was sourced from the third-party search engine Flixable, and group them into relevant clusters. This will aid in enhancing the user experience and prevent subscriber churn for the world's largest online streaming service provider, Netflix, which currently boasts over 220 million subscribers as of 2022-Q2. The dataset, which includes movies and TV shows as of 2019, will be analyzed to uncover new insights and trends in the rapidly growing world of streaming entertainment.

Objective
The objective of this project is to organize the Netflix shows into distinct clusters, where the shows within a cluster are alike and the shows in different clusters are dissimilar to one another.

Dataset
The dataset used in this project is sourced from Flixable, a third-party Netflix search engine. The data includes information on all movies and TV shows available on the streaming platform as of 2019, with a total of 7787 records and 12 attributes. Each attribute provides specific information about the movie or TV show. For more information on the dataset, please visit the Kaggle website at https://www.kaggle.com/datasets/sambhajizambre/netflix-movies-and-tv-shows-clustering?select=netflix_titles.csv.

Data Pipeline
Know Your Data: The first step in this project was to examine the various features of the dataset, understand the structure of the data and identify any patterns or trends. We looked at the shape of the data, the data types of each feature, and a statistical summary.
Exploratory Data Analysis: We conducted an exploratory analysis of the data to identify patterns and dependencies, and to draw conclusions that would be useful for further processing.
Data Cleaning: We checked for duplicated values in the dataset and then addressed any null values and outliers by imputing empty strings and dropping some of the null rows.
Textual Data Preprocessing: We used techniques such as stop word removal, punctuation removal, conversion to lowercase, stemming, tokenization, and word vectorization to prepare the textual data for clustering. We also used Principal Component Analysis (PCA) to handle the curse of dimensionality.
Cluster Implementation: We used K-Means and Agglomerative Hierarchical clustering algorithms to cluster the movies and determine the optimal number of clusters.
Content-Based Recommendation System: We built a content-based recommendation system using the similarity matrix obtained from cosine similarity, which will provide the user with 10 recommendations based on the type of movie/show they have watched.





├── README.md
├── Dataset 
│   
├── Problem Statement
│
├── Understanding Data
│
├── EDA
│   ├── Numeric & Categoric features
│   ├── Univariate Analysis
│   ├── Bivariate Analysis
│   ├── Multivariate Analysis
├──Data Cleaning
│   ├── Duplicated values
│   ├── NaN/Missing values
│   ├── Treating Outlier 
│
├── Textual Data Preprocessing
│   ├── Clustering Attributes
|   ├── Removing Stopwords
|   ├── Lowercasing words
|   ├── Removing Punctuation
|   ├── Stemming
│       ├── Snowball Stemmer
|   ├── Word Vectorization
|       ├── TF-IDF (Term Frequency - Inverse Document Frequency)
|   ├── Dimenssionality Reduction
|       ├── PCA (Principle Component Analysis)
│
├── Model Building
|   ├── Clustering Implemention
|       ├── K-Means Clustering
|           ├── Elbow Method
|           ├── Silhoutte Score Analysis
|       ├── Agglomerative Hierarchical Clustering
|           ├── Dendogram
├── Content Based Recommendation System
|
│   
├── Report
├── Presentation
├── Result
└── Reference



Conclusion
In this project, we tackled a text clustering problem in which we had to categorize and group Netflix shows into specific clusters in such a way that shows in the same cluster are similar to one another and shows in different clusters are not.



- There were approximately 7787 records and 11 attributes in the dataset.
- We started by working on the missing values in the dataset and conducting exploratory data analysis (EDA).
- It was discovered that Netflix hosts more movies than television shows on its platform, and the total number of shows added to Netflix is expanding at an 
exponential rate. Additionally, most of the shows were made in the United States.
- The attributes were chosen as the basis for the clustering of the data: cast, country, genre, director, rating, and description The TFIDF vectorizer was 
used to tokenize, preprocess, and vectorize the values in these attributes.
- 10000 attributes in total were created by TFIDF vectorization.
- The problem of dimensionality was dealt with through the use of Principal Component Analysis (PCA). Because 3000 components were able to account for more than 
80% of the variance, the total number of components was limited to 3000.
- Utilizing the K-Means Clustering algorithm, we first constructed clusters, and the optimal number of clusters was determined to be 6. The elbow method and 
Silhouette score analysis were used to get this.
- The Agglomerative clustering algorithm was then used to create clusters, and the optimal number of clusters was determined to be 7. This was obtained after 
visualizing the dendrogram.
- The similarity matrix generated by applying cosine similarity was used to construct a content-based recommender system. The user will receive ten 
recommendations from this recommender system based on the type of show they watched.
