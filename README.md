# Red-Wine-Quality-Logistic-Regression
This repository contains a logistic regression analysis of the Red Wine Quality dataset. The goal is to predict wine quality based on various physicochemical properties of the wine.

#Dataset Overview:
The dataset includes features such as:
Fixed Acidity: Acidic compounds in the wine.
Volatile Acidity: Amount of acetic acid in the wine.
Citric Acid: Citric acid content in the wine.
Residual Sugar: Sugar content after fermentation.
Chlorides: Salt content in the wine.
Free Sulfur Dioxide: Amount of free SO2 in the wine.
Total Sulfur Dioxide: Total SO2 in the wine.
Density: Density of the wine.
pH: Acidity of the wine.
Sulphates: Sulfate content in the wine.
Alcohol: Alcohol content in the wine.
Quality: Quality score (0-10) assigned by wine experts.

#Key Steps in the Analysis
Data Loading and Overview: Load the dataset using Pandas and display basic information such as shape, data types, and missing values.
Exploratory Data Analysis (EDA):
Visualize the distribution of wine quality using count plots.
Use pair plots to explore relationships between features.
Generate a correlation heatmap to identify relationships among features.
Data Preparation:
Create a binary target variable (quality_binary) where quality > 6 is labeled as 1 (good quality) and ≤ 6 as 0 (poor quality).
Split the data into training and testing sets, standardize the features.
Modeling:
Train a logistic regression model on the training data.
Predict the quality of wine on the test set.
Model Evaluation:
Generate a confusion matrix and classification report to assess model performance.
Calculate accuracy and visualize the confusion matrix using a heatmap.
Additional Visualizations:
Box plot to analyze alcohol content by quality.
Density plot of alcohol content by quality.

#Requirements
To run this analysis, you will need the following Python libraries:
numpy
pandas
seaborn
matplotlib
scikit-learn
