## Heart Disease Prediction Using Machine Learning
This project uses machine learning models to predict whether a person has heart disease based on several medical attributes. The dataset used is the popular Heart Disease dataset.

## Dataset
The dataset used is heart.csv, which contains 14 attributes including:

Age, Sex, Chest Pain Type, Resting BP, Cholesterol, Fasting Blood Sugar, etc.

target: 1 = Defective Heart, 0 = Healthy Heart

## Features
* Logistic Regression
* Decision Tree Classifier
* K-Nearest Neighbors (KNN)
* Confusion Matrix & Classification Report for model evaluation
* Predictive system for custom input

## Machine Learning Workflow
1. Data Loading & Exploration
* Loaded data using pandas
* Explored data shape, info, null values, stats


2. Preprocessing
* Split dataset into features (X) and target (Y)
* Train-Test split using train_test_split


3. Model Training
* Trained three classifiers:
* Logistic Regression
* Decision Tree 
* K-Nearest Neighbors

4. Evaluation
* Accuracy on training and test data
* Classification reports and confusion matrices
* Seaborn heatmap visualization


5. Prediction
* Built a function to predict heart disease for new input data

