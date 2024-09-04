# Heart Attack Analysis

## Overview
This project aims to analyze factors contributing to heart attacks and build predictive models to assess the risk of heart attacks based on various health parameters. The analysis involves data preprocessing, visualization, and applying multiple machine learning algorithms to predict heart attack occurrences.

## Features

- **Preprocessing**: The dataset was cleaned and prepared for analysis by handling missing values, normalizing numerical features, and encoding categorical variables. This step ensures the data is in optimal form for training machine learning models.

- **Data Visualization**: Various visualizations were created to explore relationships between features and understand the distribution of the data. These visualizations help in identifying key patterns and trends related to heart attacks.

- **Model Evaluation Metrics**:
  - **Confusion Matrix**: Used to visualize the performance of the classification models by showing true positives, false positives, true negatives, and false negatives.
  - **Accuracy**: Measures the overall correctness of the model by calculating the ratio of correctly predicted instances to the total instances.
  - **Precision**: Evaluates the accuracy of positive predictions by calculating the ratio of true positives to the sum of true and false positives.
  - **Recall**: Assesses the model's ability to identify all relevant instances by calculating the ratio of true positives to the sum of true positives and false negatives.
  - **F1 Score**: Provides a balance between precision and recall, especially useful when dealing with imbalanced datasets.

- **Machine Learning Algorithms**:
  - **Random Forest**: An ensemble method that builds multiple decision trees and merges them to get a more accurate and stable prediction.
  - **Logistic Regression**: A linear model used for binary classification tasks, predicting the probability of a heart attack.
  - **KNeighborsClassifier**: A non-parametric method used for classification by finding the majority class among the k-nearest neighbors.
  - **Gaussian Naive Bayes (Gaussian NB)**: A probabilistic classifier based on applying Bayes' theorem with strong independence assumptions between features.
  - **Support Vector Classifier (SVC)**: A powerful classification algorithm that finds the optimal hyperplane that best separates the classes.
  - **XGBClassifier**: An implementation of the eXtreme Gradient Boosting algorithm, known for its speed and performance in classification tasks.

## Getting Started

### Prerequisites
- Python 3.x
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost, and other required dependencies.

### Installation
Clone the repository and install the required libraries using `pip`.

