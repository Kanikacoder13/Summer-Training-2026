# Day 14 - Summer Training Daily Diary

## Training Domain
**Artificial Intelligence & Machine Learning (AI & ML) using Python**

---

## Objective

Today's training focused on understanding Polynomial Regression and its use in predicting house prices when the relationship between input features and the target variable is non-linear. The session covered model building, prediction, evaluation, visualization, and basic debugging during implementation.

---

## Tasks Assigned by the Industry Expert

During today's training session, the following tasks were assigned:

1. Understand the concept of Polynomial Regression.
2. Prepare the dataset for model training.
3. Generate polynomial features using Scikit-learn.
4. Build and train a Polynomial Regression model.
5. Evaluate the model using appropriate regression metrics.
6. Visualize the regression curve and compare predictions.
7. Identify and resolve common plotting errors during implementation.

---

## Practical Work Completed

During the practical session, I worked on the following activities:

- Imported the required libraries including NumPy, Pandas, Matplotlib, and Scikit-learn.
- Loaded the preprocessed House Price dataset.
- Prepared the training and testing datasets using `train_test_split()`.
- Generated polynomial features of Degree 2 using `PolynomialFeatures`.
- Built a Polynomial Regression model using `make_pipeline()`.
- Trained the model using the training dataset.
- Generated predictions for both the training and testing datasets.
- Evaluated the model using Mean Absolute Error (MAE) and R² Score.
- Attempted to visualize the Polynomial Regression curve using Matplotlib.
- Analyzed and discussed the plotting error caused by mismatched input dimensions during visualization.

---

## Topics Covered

### Introduction to Polynomial Regression
- Limitations of Linear Regression for non-linear data.
- Polynomial Regression as an extension of Linear Regression.
- Using polynomial features to model curved relationships.
- Applications of Polynomial Regression in house price prediction.

### Dataset Preparation
- Loading the preprocessed dataset.
- Selecting input features and target variable.
- Splitting the dataset into training and testing sets using `train_test_split()`.
- Using a sample dataset for visualization.

### Building the Polynomial Regression Model
- Introduction to `PolynomialFeatures`.
- Creating polynomial features of Degree 2.
- Building the regression model using `make_pipeline()`.
- Training the model with the prepared dataset.

### Model Prediction and Evaluation
- Predicting house prices using the trained model.
- Evaluating model performance using MAE and R² Score.
- Comparing predictions on training and testing datasets.

### Regression Visualization
- Visualizing actual data using a Scatter Plot.
- Plotting the Polynomial Regression curve.
- Understanding the relationship between actual and predicted values.

### Program Debugging
- Identifying plotting errors.
- Understanding the "x and y must be the same size" error.
- Importance of matching input dimensions while creating visualizations.

---

## Learning Outcomes

By the end of today's training, I was able to:

- Understand the working of Polynomial Regression.
- Differentiate between Linear Regression and Polynomial Regression.
- Generate polynomial features using Scikit-learn.
- Build and train a Polynomial Regression model.
- Predict continuous values for non-linear datasets.
- Evaluate regression models using MAE and R² Score.
- Interpret regression results through graphical visualization.
- Recognize and understand common plotting errors during implementation.

---

## Conclusion

Today's session helped me understand how Polynomial Regression can be used to model non-linear relationships in machine learning. Through practical implementation, I learned how to generate polynomial features, train and evaluate the model, visualize the results, and identify common errors during plotting. These activities strengthened my understanding of regression techniques and improved my confidence in implementing machine learning models.
