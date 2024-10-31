# Customer Review Prediction with Machine Learning

## Project Description
Differentiating machine learning models such as Logistic Regression, Random Forest, KNN, XGBoost, Naïve Bayes, and ensemble methods for classifying customer reviews as either "positive" or "negative". The objective is to predict customer satisfaction levels based on features like fulfillment time, payment type, and price, providing valuable insights to stakeholders for informed decision-making.

## Models Employed
- **Logistic Regression**
- **Random Forest**
- **K-Nearest Neighbors (KNN)**
- **Naïve Bayes**
- **XGBoost**
- **Voting Classifier** (Ensemble approach combining the top models)

## Features
- **Data Preparation**: Extensive preprocessing steps including table merging, handling missing values, outlier removal, and class balancing.
- **Feature Engineering**: Aggregation of features, such as fulfillment time and estimated delivery time, to enhance prediction accuracy.
- **Model Evaluation**: Utilized accuracy, precision, recall, and F1-score for a comprehensive performance assessment.
- **Ensemble Methods**: Implemented both hard and soft voting classifiers to leverage the strengths of individual models.

## Usage
To train the models and view evaluation metrics, simply run the .ipynb file.

## Detailed Results
The final performance metrics for each model, after extensive training and tuning, are as follows:

- **Random Forest**: Achieved highest single-model accuracy of 68.85%.
- **XGBoost**: Consistently high accuracy with 66.95%.
- **Logistic Regression**: Provided balanced performance with 63.13% accuracy.
- **Voting Classifier (Soft Voting)**: The ensemble approach with soft voting and without feature selection achieved the best overall accuracy of 69.30%.

The ensemble methods, particularly soft voting, demonstrated improved accuracy and balanced performance metrics, handling class imbalances effectively.

## Contributions
Contributions are welcome! Fork this repository and submit pull requests for any improvements or new features.
