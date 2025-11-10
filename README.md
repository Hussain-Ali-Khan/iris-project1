Iris Dataset Analysis and Classification
This notebook performs an exploratory data analysis on the Iris dataset and trains several classification models to predict the species of iris flowers based on their measurements.

Table of Contents
Introduction
Dataset Loading and Preparation
Exploratory Data Analysis
Model Training
Model Evaluation
1. Introduction
This notebook demonstrates a typical machine learning workflow using the famous Iris dataset. The goal is to classify iris flowers into one of three species (setosa, versicolor, or virginica) based on four features: sepal length, sepal width, petal length, and petal width.

2. Dataset Loading and Preparation
The Iris dataset is loaded using sklearn.datasets.load_iris. The data is then converted into a pandas DataFrame for easier manipulation and analysis. The target variable (species) is added as a new column to the DataFrame.

3. Exploratory Data Analysis
Basic descriptive statistics of the dataset are calculated and displayed. Histograms of the features are generated to visualize their distributions. A scatter plot of sepal length vs. petal length is also created to explore the relationship between these two features.

4. Model Training
The dataset is split into training and testing sets. The features are scaled using StandardScaler to ensure that all features have a similar range, which can improve the performance of some models. Three classification models are trained:

Support Vector Classifier (SVC)
Random Forest Classifier
Logistic Regression
5. Model Evaluation
The trained models are evaluated on the test set using confusion matrices and classification reports. The performance of each model is printed, including precision, recall, f1-score, and support for each class. Confusion matrices are visualized using heatmaps to show the number of correct and incorrect predictions for each class.
