# Steam-Games-Hybrid-Game-Recommendation-System
This project is a Hybrid Game Recommendation System created by combining the concepts of Sentiment Analysis, Collaborative Filtering and Metadata based Content Filtering System.

Link to Dataset :  https://cseweb.ucsd.edu/~jmcauley/datasets.html

This project is a combined work of Maahi Chatterjee, Ranjana Ajayakumar and Shivani Shivanand Suryawanshi as required for the fulfilment of the group project in our CmpE 256 : Large Scale Analytics course.

The repository includes the following:

### SteamGamesHybridRecommendationSystem.ipynb : 
Notebook containing the implemntation of Sentiment Analysis, SVD and Metadata based Content Filtering merged together to create a hybrid recommendation system. This is the main project file and more information about each step can be found in the report. As an overview, the sequence of steps that were followed are : Data Cleaning , Sentiment Analysis, Content Based Filtering using metadata (Commented with recommendation function for only getting the similar items), SVD (Commented with the recommendation function for predicting only ratings using SVD) and the final hybrid recommendation function.

### SteamGamesHybridRecommendationSystem.html : 
An HTML file of our notebook since the notebook is a big file and sometime git crashes when loading the file

### SteamGamesHybridRecommendationSystem.ipynb.zip : 
A zip file for our notebook submission because of it's size

### Autoencoder.ipynb : 
Contains an implementation to an alternative to using SVD as a latent factor model for rating prediction. More information is in the report.

### Logistic Regression_on_Sentiment_Analysis.ipynb : 
Implementation of Logistic Regression on the Sentiment Analysis performed. More information is in the report.

### Hybrid Steam Video Recommendation System(Project Report) : 
A step by step description of our project

### Dataset Files : 
2 dataset files , australian_user_reviews and steam_bundles are added in the repo. However the third file was too big for git and cannot therefore be taken from the dataset link. The missing file is australian_users_items
