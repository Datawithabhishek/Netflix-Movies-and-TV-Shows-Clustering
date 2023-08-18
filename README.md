<h1 align='center'> :microscope: Unsupervised-Clustering-Analysis-on-Netflix-Movies-And-TV Shows.</h1>

![--------------------------------------------------------------------------------------------](https://github.com/andreasbm/readme/blob/master/assets/lines/grass.png)

### This repository contains the and dataset and the research notbook consisting various aproches for clustering movies and tv shows for netflix dataset. The movies and tv shows are present in the dataset which where released during the period of 1925 to 2021.
![--------------------------------------------------------------------------------------------](https://github.com/andreasbm/readme/blob/master/assets/lines/grass.png)






<p align="center"> 
<img src="https://media.tenor.com/twG41IiAAscAAAAC/no.gif" alt="Animated gif netflix Image" height="382px">
</p>


# Problem Statement
The problem at hand involves exploring the Netflix dataset to gain insights into the content available on the platform. The dataset provides information about movies and TV shows, their attributes, and their availability in different countries. By integrating this dataset with external sources such as IMDB ratings and Rotten Tomatoes, we can extract further valuable information.

The specific tasks to be performed in this project include:

- **Exploratory Data Analysis (EDA):** Cleaned the data, unnested the Netflix content and tackled the null/missing values and conduct a thorough analysis of the dataset to uncover trends, patterns, and correlations among different attributes.
- **Understanding Content Availability:** Determine the types of content available in different countries and identify any variations or preferences.
- **Analyzing Netflix's Focus:** Investigate whether Netflix has been increasingly focusing on TV shows rather than movies in recent years.
- **Clustering Similar Content:** Utilize text-based features to cluster similar content, enabling the development of a content-based recommender system.





##  💾 Project Files Description

<p>This Project includes :-
  <li>Google Colab NoteBook</li>
  <li>Project Summary (with the GitHub Repo link inside)</li>
  <li>Presentation Video</li>
</p>


### Input Files:
  <li><b>NETFLIX MOVIES AND TV SHOW CLUSTERING.csv</b> - Contains the records of movies and tv show released during 1925 to 2021.</li>

### Data Source:
- [Dataset](https://drive.google.com/file/d/1gt4yzUiQ1IB8kxB5YglidWtyqn_xraWG/view?usp=sharing) - Dataset taken from AlmaBetter


## 🗺️ Dataset Description

The dataset contains 7,787 records and 11 features, including information about movies and TV shows from 1925 to 2021. The dataset includes two types of content: movies (71.1%) and TV shows (28.3%). The most frequent rating is TV-MA (Mature Audience only) followed by Teen and older. The highest number of content was added in 2019. The highest number of content is available in the months of October, December, and January.


## 🔎 Key Findings

>* Most of the content is of the type of movie (71.1%).
>* The highest number of aquitted/created content was added in 2019.
>* The highest number of content is available in the months of October, December, and January.
>* The top genres where most of the movies and TV shows are listed are Dramas, International Movies, and Comedies.
>* The optimal number of clusters for the dataset is four.
>* The developed recommendation system is expected to improve the user experience and reduce subscriber churn for Netflix, which currently has over 220 million subscribers.

## 🛠️ Builds with

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)

![NumPy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)

![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)

![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

![Seaborn](https://img.shields.io/badge/Seaborn-blue?style=for-the-badge&logo=Seaborn)

![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)

![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)

![GoogleColab](https://img.shields.io/badge/GoogleColab-orange?style=for-the-badge&logo=GoogleColab)






# Project Summary
The aim of this project is to analyze the Netflix dataset, which includes information on movies and TV shows available on the platform until 2019. With over 220 million subscribers, Netflix is the world's largest online streaming service provider. By analyzing and clustering the content, we can enhance the user experience through a personalized recommendation system, potentially reducing subscriber churn.

The project follows a step-by-step process, as outlined below:

- **Handling Missing Values:** Address any null or missing values present in the dataset.
- **Dealing with Nested Columns:** Process nested columns such as director, cast, listed_in, and country to facilitate clear visualization and analysis.
- **Rating Binning:** Categorize ratings into appropriate categories, including adult, children's, family-friendly, and not rated content.
- **Exploratory Data Analysis (EDA):** Perform in-depth EDA on various attributes, uncovering valuable findings to aid in churn prevention.
- **Cluster Creation:** Create clusters using attributes such as director, cast, country, genre, rating, and description. Tokenize, preprocess, and vectorize the attribute values using TF-IDF vectorizer.
- **Clustering Algorithms:** Employ K-Means Clustering and Agglomerative Hierarchical Clustering algorithms to construct two distinct types of clusters. Determine the optimal number of clusters using methods like the Elbow method and Dendrogram.







