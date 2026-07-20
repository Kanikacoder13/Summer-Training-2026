# Day 16 - Summer Training Report

# Logistic Regression for Classification

**Training Domain:** Artificial Intelligence & Machine Learning (AI & ML) using Python

---

## Objective

The objective of today's session was to understand Logistic Regression as a supervised Machine Learning algorithm for classification problems. The session focused on building Binary and Multiclass Classification models, evaluating model performance using different metrics, interpreting confusion matrices and classification reports, and comparing different classification approaches using the Titanic dataset.

---

## Topics Covered

### 1. Introduction to Logistic Regression

- Understanding Logistic Regression as a supervised Machine Learning algorithm.
- Difference between Regression and Classification problems.
- Binary Classification and Multiclass Classification.
- Applications of Logistic Regression in Machine Learning.

### 2. Binary Classification

- Predicting passenger survival using the Titanic dataset.
- Selecting input features and target variable.
- Splitting the dataset into training and testing sets.
- Training the Logistic Regression model.
- Generating predictions for unseen data.

### 3. Model Evaluation

- Calculating model accuracy.
- Understanding the Confusion Matrix.
- Interpreting:
  - True Positive (TP)
  - True Negative (TN)
  - False Positive (FP)
  - False Negative (FN)
- Understanding the Classification Report.
- Evaluation metrics:
  - Precision
  - Recall
  - F1-Score
  - Accuracy

### 4. Multiclass Classification

- Predicting Passenger Class (`Pclass`) using Logistic Regression.
- Understanding multiclass classification problems.
- Introduction to:
  - One-vs-Rest (OvR)
  - Multinomial (Softmax) Classification
- Training and testing a multiclass Logistic Regression model.

### 5. Multiclass Model Evaluation

- Evaluating multiclass predictions.
- Generating a multiclass Confusion Matrix.
- Interpreting the Classification Report for multiple classes.
- Comparing prediction performance across different passenger classes.

### 6. Model Comparison

- Comparing Binary Classification and Multiclass Classification.
- Understanding:
  - Number of classes
  - Prediction methods
  - Output interpretation
  - Confusion Matrix differences
  - Sigmoid vs Softmax functions

### 7. Practice Exercises

- Improving Binary Classification by adding the **Pclass** feature.
- Comparing prediction accuracy before and after feature addition.
- Understanding the effect of feature selection on model performance.
- Experimenting with different probability thresholds using `predict_proba()`.
- Observing the effect of threshold changes on classification results and confusion matrices.

---

## Practical Activities Performed

During the practical session, I performed the following activities:

- Loaded and explored the Titanic dataset.
- Selected appropriate input features and target variables.
- Split the dataset into training and testing sets.
- Built and trained a Binary Logistic Regression model.
- Generated survival predictions for the testing dataset.
- Evaluated model performance using Accuracy, Confusion Matrix, and Classification Report.
- Built and trained a Multiclass Logistic Regression model for passenger class prediction.
- Generated predictions for multiclass classification.
- Compared Binary and Multiclass Logistic Regression models.
- Added an additional feature (`Pclass`) to improve binary classification performance.
- Experimented with custom probability thresholds using `predict_proba()`.
- Analyzed how changing the decision threshold affected prediction results.

---

## Key Learning Outcomes

By the end of today's session, I was able to:

- Understand the working principle of Logistic Regression.
- Differentiate between Binary and Multiclass Classification.
- Train Logistic Regression models using Scikit-learn.
- Evaluate classification models using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.
- Understand the concepts of One-vs-Rest and Multinomial Classification.
- Analyze the impact of feature selection on model performance.
- Understand how decision thresholds influence classification outcomes.
- Compare different classification approaches for Machine Learning applications.

---

## Conclusion

Today's session provided practical knowledge of Logistic Regression for both Binary and Multiclass Classification using the Titanic dataset. Through model training, evaluation, comparison, and hands-on exercises, I learned how to develop classification models, interpret evaluation metrics, improve prediction performance through feature selection, and analyze the effect of decision thresholds. These concepts form an essential foundation for solving real-world classification problems in Machine Learning.
