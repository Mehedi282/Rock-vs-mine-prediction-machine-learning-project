# Rock-vs-mine-prediction-machine-learning-project

[Rock vs Mine Prediction](https://colab.research.google.com/drive/1CL2dgkDDciGjLaQVyBdesPyoGQ2V_jmI#scrollTo=VJZTzFDarmQ_)

This repository contains a machine learning project that uses Logistic Regression to classify whether an object is a rock or a mine based on sonar data.

Table of Contents
Introduction
Dataset
Usage
Model
Results


Introduction
The project involves using sonar signals to distinguish between rocks and mines. It implements a Logistic Regression model to make predictions. The project uses common Python libraries such as pandas, numpy, and scikit-learn to preprocess the data and build the model.

Dataset
The dataset used in this project is the Sonar, Mines vs. Rocks dataset, which consists of 208 samples with 60 features each, representing sonar signal intensities at different angles.

The script will:

Load and preprocess the dataset using pandas and numpy.
Split the data into training and testing sets.
Train a Logistic Regression model using scikit-learn's LogisticRegression.
Evaluate the model's performance using accuracy score.



Model
This project uses Logistic Regression as the classification algorithm. The following libraries were used:

pandas for data manipulation and analysis.
numpy for numerical computations.
scikit-learn for model training and evaluation (LogisticRegression, train_test_split, accuracy_score).
Here’s a quick overview of the steps:

Data Splitting: The dataset is split into training and testing sets using train_test_split.
Model Training: The Logistic Regression model is trained on the training set.
Model Evaluation: The model’s performance is measured on the test set using accuracy score.
