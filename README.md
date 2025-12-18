# Mushroom Classification

## Overview
This project builds a supervised machine learning classification system to predict whether a mushroom is edible or poisonous. The workflow includes exploratory data analysis, data preprocessing, feature encoding, and training multiple classification models using Python.

## Dataset
- Source: UCI / Kaggle Mushroom Classification Dataset
- Records: 8,124 mushroom samples
- Target variable:
  - Edible (0)
  - Poisonous (1)
- Features: Cap shape, cap colour, odor, gill size, gill colour, bruises, and other categorical attributes

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Approach
- Performed exploratory data analysis using count plots and visualisations
- Cleaned and prepared categorical data for modelling
- Encoded features using one-hot encoding and label encoding
- Removed features that caused data leakage
- Split data into training and testing sets (80/20)
- Trained and evaluated multiple classification models:
  - Random Forest Classifier
  - Logistic Regression
  - Decision Tree Classifier

## Model Evaluation
- Evaluated models using:
  - Accuracy score
  - Classification report (precision, recall, F1-score)
  - Confusion matrices
- Analysed feature importance for the Random Forest model to identify influential predictors

## Results
- Random Forest achieved **~99% accuracy**
- Logistic Regression and Decision Tree models also achieved high classification performance
- Results confirm strong separability between edible and poisonous mushroom classes

## Project Structure
