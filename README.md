Netflix-Movies-and-TV-Shows-Clustering
AlmaBetter Capstone Project
![1_MlYDmLXuoeOLHiJoIIjsRg ](https://user-images.githubusercontent.com/113963339/213934250-58cf1d46-d11c-43dd-af89-741483388519.jpg)



Objectives:
Conduct Exploratory Data Analysis.

Try understanding what type content is available in different countries.

Check if Netflix is increasingly focusing on TV rather than movies in recent years.

Clustering similar content by matching text-based features.

Methods used:
Descriptive Statistics.

Data Visualization.

Machine Learning.

Libraries utilized:
NumPy and Pandas - For dataset cleaning and analysis.

Matplotlib, Plotly and Seaborn - For Data Visualization.

SkLearn and nltk - For machine learning and clustering.

Project Overview
Netflix, is an American subscription streaming service and production company. It was founded in 1997 by Reed Hastings and Marc Randolph in Scott’s Valley, California.

It offers a library of films and television series through distribution deals as well as its own productions, known as Netflix Originals.

Our objective is to conduct an Exploratory Data Analysis to understand what content is available in different countries and if Netflix has been increasingly focusing on TV rather than movies in recent years. And use these insights to cluster similar content by matching text-based features.

After loading the data, we start by observing the first and last five values to understand the dataset. This is followed by feature engineering to extract new variables from the datetime variable date_added.

This cleaned data is then used to conduct EDA in order to understand it better and identify the underlying trends.

Once obtained the required insights from the EDA, we start with Pre-processing the text data by removing the punctuation, and, stop words. This filtered data is passed through TF - IDF Vectorizer since we are conducting a text-based clustering and the model needs the data to be vectorized in order to predict the desired results.

Then clusters were built using the Agglomerative clustering algorithm, and the optimal number of clusters came out to be 12. This was obtained after visualizing the dendrogram.

A content based recommender system was built using the similarity matrix obtained after using cosine similarity. This recommender system will make 10 recommendations to the user based on the type of show they watched.
