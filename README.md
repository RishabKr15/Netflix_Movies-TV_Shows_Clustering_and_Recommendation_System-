# Netflix_Movies_and_TV_Shows_Clustering

![Netflix-Symbol](https://github.com/Hritikrai55/Netflix_Movies_and_TV_Shows_Clustering/assets/129497779/d3c6d8ae-137c-4e6d-8da7-00b4f094bbbf)

The main objective of this project was to analyze a dataset of TV shows and movies available on Netflix as of 2019. By utilizing NLP techniques, our aim was to group the content into relevant clusters and create a recommendation system that would enhance the user experience and prevent subscriber churn. With over 200 million subscribers, Netflix is the largest online streaming service provider, and it is crucial to continually improve its offerings.

We began with addressing missing values in the dataset and handling nested columns such as director, cast, listed_in, and country. This allowed for a more organized and comprehensive analysis of the data.

To categorize the content effectively, we binned the rating attribute into appropriate categories, including adult, children's, family-friendly, and not rated content. This classification helps in delivering targeted recommendations based on viewer preferences and age appropriateness.

Exploratory data analysis (EDA) was conducted to gain valuable insights into various attributes within the dataset. This process involved examining patterns, distributions, and relationships in the data, providing a deeper understanding of the content available on Netflix.

To create clusters, we employed NLP techniques by tokenizing, preprocessing, and vectorizing attributes such as director, cast, country, genre, rating, and description using the TFIDF vectorizer. This allowed us to quantify textual data and identify similarities among TV shows and movies.

Dimensionality reduction was performed using Principal Component Analysis (PCA) to improve performance and computational efficiency.

Two clustering algorithms, namely K-Means Clustering and Agglomerative Hierarchical Clustering, were used to create distinct clusters within the data. The optimal number of clusters was determined using evaluation metrics such as the Elbow method, Silhouette score, and dendrogram analysis.

Finally, we developed a content-based recommender system using the cosine similarity matrix. This system analyzed the user's viewing history and provided personalized recommendations based on similarities with other content. By delivering tailored suggestions, the recommender system aimed to improve user satisfaction and reduce churn.

In conclusion, this project successfully analyzed the Netflix dataset of TV shows and movies using NLP techniques. By clustering the content and developing a content-based recommender system, we aimed to enhance the user experience and mitigate subscriber churn for Netflix. The findings and recommendations from this project can contribute to the continuous growth and success of Netflix in the highly competitive streaming entertainment industry.
