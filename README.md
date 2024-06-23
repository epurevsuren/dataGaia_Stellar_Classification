# Stellar Classification with Gaia Data

## Overview
This project leverages the extensive Gaia dataset from the European Space Agency to classify stellar objects based on their spectral types using machine learning techniques. The primary goal is to accurately predict the spectral class of celestial objects, helping enhance our understanding of the Milky Way's structure.

## Data Source
The dataset used in this project comes from the Gaia mission, which surveys nearly two billion celestial objects to map the Milky Way with unprecedented precision.

## Objectives
- **Data Preprocessing:** Clean the data by handling missing values and outliers.
- **Feature Engineering:** Optimize feature selection to improve model accuracy.
- **Model Training:** Train and evaluate multiple classification models to find the most accurate one.
- **Prediction:** Use the best model to predict the spectral classes of unknown celestial objects.

## Challenges
- Managing missing values and transforming features.
- Selecting and tuning multiple classification algorithms.
- Ensuring the interpretability and scientific validity of the results.

## Techniques Used
- **Data Cleaning:** Techniques like imputation to handle missing data.
- **Feature Transformation:** Normalization, discretization, and binarization to prepare data for modeling.
- **Model Evaluation:** Utilized various models including Logistic Regression, Random Forest, SVM, KNN, and Gradient Boosting.
- **Visualization:** Histograms, density plots, and correlation heatmaps to explore data distributions and relationships.

## Results
The Random Forest model provided the best results, achieving an accuracy of approximately 99.7% on the validation set.

## Technologies Used
- **Python**
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
