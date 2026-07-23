# Day 19 - Summer Training Report

# Random Forest Classification and Model Comparison

**Training Domain:** Artificial Intelligence & Machine Learning (AI & ML) using Python

---

## Objective

The objective of today's session was to understand Random Forest as an ensemble learning algorithm and compare its performance with Decision Tree and Logistic Regression models. The session focused on building Random Forest models, evaluating classification performance, analyzing feature importance, and comparing different classification algorithms.

---

## Topics Covered

### 1. Introduction to Random Forest

- Understanding Ensemble Learning.
- Introduction to Random Forest.
- Limitations of a single Decision Tree.
- Advantages of combining multiple decision trees.

### 2. Working of Random Forest

- Bootstrap Aggregation (Bagging).
- Random sampling with replacement.
- Feature Subspace Sampling.
- Majority Voting for final prediction.
- Reducing overfitting through ensemble methods.

### 3. Building a Random Forest Classifier

- Training a Random Forest model using Scikit-learn.
- Setting the number of trees (`n_estimators`).
- Limiting tree depth using `max_depth`.
- Generating predictions for unseen data.

### 4. Model Evaluation

- Evaluating model accuracy.
- Cross-validation.
- Classification Report.
- Confusion Matrix.
- Comparing training and testing performance.

### 5. Feature Importance

- Understanding Gini Importance.
- Identifying the most influential features.
- Comparing Random Forest feature importance with Logistic Regression coefficients.
- Interpreting feature importance graphs.

### 6. Classifier Comparison

- Comparing:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Comparing test accuracy and cross-validation accuracy.
- Understanding strengths and limitations of each classifier.

### 7. Practical Exercises

- Experimenting with different values of `n_estimators`.
- Tuning `min_samples_leaf`.
- Performing Permutation Feature Importance.
- Comparing Decision Tree and Random Forest decision boundaries.
- Understanding the effect of hyperparameter tuning on model performance.

---

## Practical Activities Performed

During the practical session, I performed the following activities:

- Built a Random Forest Classifier using Scikit-learn.
- Trained the model using the Titanic dataset.
- Generated predictions for the testing dataset.
- Evaluated model performance using Accuracy, Confusion Matrix, and Classification Report.
- Performed Cross-Validation to assess model reliability.
- Analyzed feature importance using Gini Importance.
- Compared feature importance with Logistic Regression coefficients.
- Compared the performance of Logistic Regression, Decision Tree, and Random Forest models.
- Experimented with different values of `n_estimators`.
- Performed hyperparameter tuning using `min_samples_leaf`.
- Explored Permutation Feature Importance.
- Compared Decision Tree and Random Forest decision boundaries.

---

## Key Learning Outcomes

By the end of today's session, I was able to:

- Understand the working principle of Random Forest.
- Explain the concept of Ensemble Learning.
- Build and evaluate Random Forest models.
- Interpret Classification Reports and Confusion Matrices.
- Analyze feature importance using tree-based models.
- Compare the performance of different classification algorithms.
- Understand how ensemble methods improve prediction accuracy and reduce overfitting.

---

## Conclusion

Today's session introduced Random Forest as a powerful ensemble learning technique for classification problems. Through practical implementation and comparative analysis, I learned how Random Forest improves upon Decision Trees by combining multiple models, reducing overfitting, and providing more reliable predictions. The session also strengthened my understanding of feature importance and model comparison, which are essential for selecting appropriate Machine Learning algorithms.
