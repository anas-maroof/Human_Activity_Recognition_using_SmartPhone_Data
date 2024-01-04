# Human_Activity_Recognition_using_SmartPhone_Data

# Overview
This project focuses on classifying human activities using smartphone sensor data. The dataset comprises recordings of 30 participants, each performing six activities while wearing a smartphone with embedded sensors. Activities include WALKING, WALKINGUPSTAIRS, WALKINGDOWNSTAIRS, SITTING, STANDING, and LAYING. With a detailed preprocessing pipeline, including noise filtering and feature extraction, the dataset is split into training and testing sets. The project involves Exploratory Data Analysis (EDA) to understand feature distributions, followed by the implementation of machine learning models such as Logistic Regression, Linear SVM, Kernel SVM, Decision Tree, and Random Forest for activity classification.

# Experiment Description
Participants aged 19-48 wore a Samsung Galaxy S II on their waist, capturing 3-axial linear acceleration and 3-axial angular velocity at 50Hz. The dataset's random partitioning allocates 70% for training and 30% for testing. Signal preprocessing involves noise filtering and fixed-width sliding windows, leading to feature extraction from time and frequency domains.

# Project Contents
Importing Necessary Libraries: Initialization with required libraries.
Loading Data: Retrieving the human activity dataset.
Data Preprocessing: Handling duplicates, missing values, and checking class imbalance.
Exploratory Data Analysis (EDA): Analyzing key features, visualizing data using t-SNE.
Model Prediction and Evaluation: Implementing Logistic Regression, Linear SVM, Kernel SVM, Decision Tree, and Random Forest models with hyperparameter tuning and cross-validation.
# Usage
Clone the repository.
Run the provided Jupyter notebook to execute the entire data analysis and modeling pipeline.
Explore insights gained from EDA and evaluate the performance of various machine learning models.
Feel free to contribute, adapt, or utilize this project for your own human activity recognition endeavors. Let's delve into the fascinating world of machine learning applied to daily activities!
