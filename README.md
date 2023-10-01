# Netflix-Movies-And-TV-Shows-Clustering-Project
# Netflix Content Clustering and EDA

This repository contains the code and findings for a data-driven approach to clustering and exploratory data analysis (EDA) of Netflix movies and TV shows. The goal of this project is to organize Netflix's extensive content library into distinct categories using unsupervised machine learning methods and to gain insights into its diverse characteristics through EDA. This approach aims to enhance the user experience by offering personalized content recommendations and informing content-related decisions.
![image](https://github.com/DevanshA2511/Netflix-Movies-And-TV-Shows-Clustering-Project/assets/130047748/088755bd-a799-40af-b6e5-ce5fe765f5fd)

## Project Highlights

### Clustering Netflix Content

- **Data Preprocessing:** The dataset includes various attributes such as director, cast, country, genre, rating, and description. Textual attributes were preprocessed and vectorized using the TFIDF vectorizer, resulting in a high-dimensional dataset with 10,000 attributes. Principal Component Analysis (PCA) was employed to reduce dimensionality while retaining over 95% of the variance.

- **K-Means Clustering:** Utilizing K-Means clustering, the content was categorized into 7 distinct clusters. The optimal number of clusters was determined using the elbow method and Silhouette score analysis.

- **Agglomerative Clustering:** Hierarchical clustering was implemented, revealing an optimal number of 5 clusters based on dendrogram visualization.

- **DBSCAN Clustering:** DBSCAN clustering was also implemented, resulting in 17 clusters, although the metric scores indicated suboptimal performance for this approach.

- **Content-Based Recommender System:** A content-based recommender system was established using cosine similarity, enabling personalized recommendations based on user viewing preferences.

### Exploratory Data Analysis (EDA)

The EDA of Netflix content revealed several key insights:

- Netflix primarily offers more movies than TV shows within its content library.

- The predominant content rating on Netflix is TV-MA (Mature Audiences), indicating a strong presence of content suitable for mature viewers.

- The United States leads in terms of content production on Netflix, with India and the United Kingdom following closely.

- Dramas are the most prevalent genre on Netflix, closely followed by Comedies and Documentaries, indicating a wide array of content genres available for viewers.

- Word Cloud analysis of movie descriptions highlights recurring keywords like love, family, young, life, and world, shedding light on prevalent themes in Netflix movie descriptions.

- Correlation analysis reveals insights into the relationship between a movie's duration, release year, number of reviews, and rating.

- Pairplot analysis showcases correlations between various attributes, such as the year of release, number of reviews, movie rating, and duration.

## Project Benefits

- **Enhanced User Experience:** Clustering enables personalized content recommendations, leading to improved user engagement and satisfaction.

- **Data-Informed Content Decisions:** Understanding user behavior trends informs content acquisition, production, and removal strategies, optimizing the content library.

- **User Retention and Revenue Growth:** Personalized recommendations and a well-curated content library contribute to higher user retention and increased revenue.

## Usage

- Clone this repository to access the code and dataset used for clustering and EDA.
- Follow the Jupyter notebooks for step-by-step implementation and analysis.
- Use the findings to make informed decisions about content categorization and user recommendations.

## Dependencies

Ensure you have the following Python libraries installed:

- numpy
- pandas
- matplotlib
- seaborn
- sklearn (scikit-learn)
