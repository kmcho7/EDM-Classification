# Electronic Music Subgenre Classification
 Author: Kevin Cho
 
 This project aims to classify electronic music songs into subgenres using their audio features. The dataset contains 23 subgenre classes and 92 audio features such as tempo, loudness, and entropy. Dimensionality reduction was explored using Principal Component Analysis (PCA). Various classification models were trained and hyperparameters were tuned using cross-validation. The methods explored include Logistic Regression, Support Vector Machine (SVM), Neural Network, Random Forest, and K-Nearest Neighbors (KNN). The best accuracy achieved on the test data was 57% using the Random Forest model with the original 92 features.

## Technology

 Data exploration and modeling was done using Python and scikit-learn in a Jupyter Notebook.

 python version     :  3.8.5\
 numpy version      :  1.24.3\
 pandas version     :  2.0.2\
 matplotlib version :  3.7.1\
 sklearn version    :  1.2.2

## Project Files
 1. EDM-class-report.pdf : A report that discusses the project methodology, results, and conclusion in-depth.
 2. EDM-class-code.ipynb : A Jupyter Notebook that contains exploratory data analysis and model training/tuning/testing code.
 3. beatsdataset201611_full.csv : “Electronic Music Features” dataset from Kaggle containing 2,300 rows x 93 columns. The first 92 columns represent the audio features and the last column represents the subgenre classes. Each row represents a song and there are 100 of the top songs for each of 23 distinct subgenres (classes) according to Beatport.com in November 2016. https://www.kaggle.com/datasets/caparrini/electronic-music-features-201611-beatporttop100
