
# Random Forest Classifier for Social Network Ads

This project demonstrates the use of a Random Forest Classifier to predict user behavior based on demographic data. The dataset used is "Social_Network_Ads.csv," where the goal is to predict whether a user purchases a product based on their age and estimated salary.

## Dataset
The dataset consists of user demographic data:

- Age
- Estimated Salary
- Purchased (Target variable: 0 for no, 1 for yes)
## Workflow
1. Data Preprocessing

- Read the dataset using pandas.
- Split the features (X) and target variable (y).
- Divide the dataset into training and test sets using an 80-20 split.

2. Model Implementation

- Train a Random Forest Classifier on the training dataset.
- Use the trained model to predict outcomes for the test dataset.

3. Evaluation

- Assess the model's accuracy and performance.
- Visualize decision boundaries (optional).
## Prerequisites
- Python 3.8 or later
- Libraries:
  - numpy
  - pandas
  - matplotlib
  - scikit-learn

## Key Features

- Train-Test Split: The dataset is split into training (75%) and testing (25%) datasets to ensure robust evaluation.
- Random Forest Classifier: A powerful ensemble learning method used for classification tasks.
- Data Visualization: Optionally visualize the decision boundaries for better interpretability.
