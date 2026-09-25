# Iris Flower Classification using Machine Learning

## Overview
This project performs Exploratory Data Analysis (EDA) and builds Machine Learning models to classify iris flowers into their respective species based on sepal and petal measurements. It uses the classic Iris dataset and compares the performance of Logistic Regression and Random Forest Classifier.

---

## A chart explaining the complete flow:
<img width="868" height="1041" alt="image" src="https://github.com/user-attachments/assets/c82fd3db-65bc-414e-8b56-e06dfe31935b" />


## Tech Stack and Libraries
* Language: Python 
* Data Manipulation: pandas, numpy
* Data Visualization: matplotlib, seaborn
* Machine Learning: scikit-learn (LogisticRegression, RandomForestClassifier, cross-validation metrics)

---

## Exploratory Data Analysis (EDA)
The project explores feature distributions and correlations using multiple visualization techniques:
* Box Plots: To analyze petal width distributions across species.
* Histograms: To check data distribution for individual features like sepal length.
* Scatter Plots and Pairplots: To visualize multi-feature relationships across all potential combinations.

---

## Machine Learning Workflow
1. **Data Preprocessing:** Dropped unnecessary columns (Id) and separated features from the target variable (Species).
2. **Train Test Split:** Split the data into an 80% training set and a 20% testing set.
3. **Model 1 (Logistic Regression):** Trained with cross-validation (cv = 5) and evaluated using accuracy scores, classification reports, and confusion matrices.
4. **Model 2 (Random Forest Classifier):** Built an ensemble classifier and visualized performance with a confusion matrix heatmap.

---

## Quick Start
1. Ensure you have the required libraries installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
