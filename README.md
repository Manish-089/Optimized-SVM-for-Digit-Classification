Handwritten Digits Recognition using Machine Learning
This repository contains a Jupyter Notebook that explores the Pen-Based Recognition of Handwritten Digits Dataset from the UCI Machine Learning Repository. The goal is to build a machine learning model to accurately classify handwritten digits.

Dataset Overview
The dataset consists of scanned images of handwritten digits, with 10 classes representing digits 0 through 9. It was collected from 44 subjects.

Data Reference Links:
TUBITAK Article
UCI Machine Learning Repository: Pen-Based Recognition of Handwritten Digits Dataset
Notebook Contents
The notebook covers the following steps:

Data Loading: Loading the pendigits_txt.csv file into a pandas DataFrame.
Understanding Data & EDA:
Exploring the shape and information of the dataset.
Checking for duplicate entries.
Generating descriptive statistics.
Analyzing the distribution of the target variable ('class').
Visualizing features using boxplots and distribution plots.
Identifying potential outliers using the interquartile range (IQR) method.
Visualizing correlations between features using a heatmap.
Modeling:
Splitting the data into training and testing sets.
Implementing and evaluating three classification models:
Support Vector Machine (SVM) Classifier
Decision Tree (DT) Classifier
Random Forest (RF) Classifier
Using GridSearchCV to find the best hyperparameters for each model.
Evaluating model performance using confusion matrices, classification reports, Class Prediction Error plots, and ROC AUC curves.
Comparing Models: Comparing the performance of the trained models based on accuracy and F1-score.
Final Model & Prediction:
Selecting the best-performing model (SVM in this case) as the final model.
Training the final model on the entire dataset.
Saving and loading the final model using pickle.
Making predictions on new data using the final model.
Requirements
To run this notebook, you will need the following libraries installed:

pandas
numpy
seaborn
matplotlib
skimpy
missingno
cufflinks
scikit-learn
yellowbrick
