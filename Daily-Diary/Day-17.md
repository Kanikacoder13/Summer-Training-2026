# Day 17 - Summer Training Daily Diary

## Training Domain
**Artificial Intelligence & Machine Learning (AI & ML) using Python**

---

## Objective

Today's session introduced Logistic Regression, a supervised Machine Learning algorithm used for classification problems. The main focus was on building Binary and Multiclass Classification models, evaluating their performance using different metrics, and understanding how Logistic Regression can be applied to real-world datasets like Titanic.

---

## Tasks Assigned by the Industry Expert

The following tasks were assigned during today's training session:

1. Understand the basics of Logistic Regression.
2. Build a Binary Classification model using the Titanic dataset.
3. Evaluate the model using different classification metrics.
4. Develop a Multiclass Classification model.
5. Compare Binary and Multiclass Logistic Regression.
6. Improve model performance by experimenting with different features and prediction thresholds.

---

## Work Performed

During the practical session, I completed the following activities:

- Loaded and explored the Titanic dataset using Pandas.
- Selected suitable input features and target variables for classification.
- Split the dataset into training and testing sets.
- Built and trained a Binary Logistic Regression model to predict passenger survival.
- Generated predictions for the testing dataset.
- Evaluated the model using Accuracy, Confusion Matrix, and Classification Report.
- Built a Multiclass Logistic Regression model to predict passenger class.
- Compared the performance of Binary and Multiclass Classification models.
- Added the **Pclass** feature to observe its effect on prediction accuracy.
- Used `predict_proba()` to experiment with different probability thresholds.
- Analyzed how changing the decision threshold affected model predictions and the confusion matrix.

---

## Topics Covered

### Introduction to Logistic Regression
- Logistic Regression as a supervised Machine Learning algorithm.
- Difference between Regression and Classification problems.
- Binary Classification and Multiclass Classification.
- Applications of Logistic Regression.

### Binary Classification
- Predicting passenger survival using the Titanic dataset.
- Selecting input features and target variable.
- Splitting data into training and testing sets.
- Training the Logistic Regression model.
- Making predictions on unseen data.

### Model Evaluation
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

### Multiclass Classification
- Predicting Passenger Class (`Pclass`) using Logistic Regression.
- Introduction to:
  - One-vs-Rest (OvR)
  - Multinomial (Softmax) Classification
- Training and testing a multiclass classification model.

### Model Comparison
- Comparing Binary and Multiclass Classification.
- Difference in prediction methods and outputs.
- Understanding Sigmoid and Softmax functions.
- Comparing confusion matrices for different classification tasks.

### Practice Exercises
- Improving Binary Classification by adding the **Pclass** feature.
- Comparing model performance before and after feature addition.
- Experimenting with different probability thresholds using `predict_proba()`.
- Observing the effect of threshold changes on prediction accuracy.

---

## Learning Outcomes

At the end of today's session, I was able to:

- Understand the working principle of Logistic Regression.
- Differentiate between Binary and Multiclass Classification problems.
- Build and train Logistic Regression models using Scikit-learn.
- Evaluate classification models using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.
- Understand the concepts of One-vs-Rest and Multinomial Classification.
- Analyze how feature selection and probability thresholds affect model performance.
- Interpret classification results for different Machine Learning tasks.

---

## Conclusion

Today's practical session gave me a clear understanding of Logistic Regression and its use in solving classification problems. By working with the Titanic dataset, I learned how to build, evaluate, and compare Binary and Multiclass Classification models using different performance metrics. I also understood how feature selection and decision thresholds can influence prediction accuracy, making this session an important step in learning Machine Learning classification techniques.
