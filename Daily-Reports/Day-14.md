# Day 14 - Summer Training Report

# Polynomial Regression for House Price Prediction

**Training Domain:** Artificial Intelligence & Machine Learning (AI & ML) using Python

---

## Objective

The objective of today's session was to understand Polynomial Regression and its application in predicting house prices when the relationship between input features and the target variable is non-linear. The session focused on building a Polynomial Regression model, training it using Scikit-learn, evaluating its performance, and visualizing the regression curve.

---

## Topics Covered

### 1. Introduction to Polynomial Regression

- Understanding the limitations of Linear Regression for non-linear data.
- Introduction to Polynomial Regression as an extension of Linear Regression.
- Learning how polynomial features help model curved relationships.
- Real-world application of Polynomial Regression in house price prediction.

### 2. Dataset Preparation

- Loading the preprocessed House Price dataset using Pandas.
- Importing the required Python libraries.
- Selecting input features and target variable.
- Creating training and testing datasets using `train_test_split()`.
- Using a random sample of the dataset for better visualization.

### 3. Building the Polynomial Regression Model

- Introduction to `PolynomialFeatures`.
- Creating polynomial features of Degree 2.
- Building the regression pipeline using:
  - `PolynomialFeatures`
  - `LinearRegression`
  - `make_pipeline()`
- Training the Polynomial Regression model on the training dataset.

### 4. Model Prediction

- Predicting house prices using the trained Polynomial Regression model.
- Generating predictions for both training and testing datasets.
- Understanding how polynomial features improve model fitting for non-linear relationships.

### 5. Model Evaluation

- Evaluating model performance using:
  - Mean Absolute Error (MAE)
  - R² Score (Coefficient of Determination)
- Comparing prediction accuracy on training and testing datasets.
- Understanding the significance of regression evaluation metrics.

### 6. Regression Visualization

- Visualizing actual house price data using Scatter Plot.
- Plotting the Polynomial Regression curve.
- Understanding the relationship between actual and predicted values.
- Interpreting curved regression models for non-linear datasets.

### 7. Program Debugging

- Identifying plotting errors during visualization.
- Understanding the "x and y must be the same size" error.
- Discussing the importance of matching input dimensions while creating plots.

---

## Practical Activities Performed

During the practical session, I performed the following activities:

- Imported NumPy, Pandas, Matplotlib, and Scikit-learn libraries.
- Loaded the preprocessed House Price dataset.
- Prepared training and testing datasets using `train_test_split()`.
- Created Polynomial Features of Degree 2.
- Built a Polynomial Regression model using `make_pipeline()`.
- Trained the regression model using the training dataset.
- Generated predictions for both training and testing data.
- Evaluated model performance using MAE and R² Score.
- Attempted to visualize the Polynomial Regression curve using Matplotlib.
- Analyzed and discussed the plotting error caused by mismatched input dimensions during visualization.

---

## Key Learning Outcomes

By the end of today's session, I was able to:

- Understand the concept of Polynomial Regression.
- Differentiate between Linear Regression and Polynomial Regression.
- Generate polynomial features using Scikit-learn.
- Build and train a Polynomial Regression model.
- Predict continuous values using a non-linear regression model.
- Evaluate regression models using MAE and R² Score.
- Visualize regression results using graphical techniques.
- Recognize common plotting errors and understand the importance of matching data dimensions during visualization.

---

## Conclusion

Today's session introduced Polynomial Regression as an effective technique for modeling non-linear relationships in Machine Learning. Through practical implementation, I learned how to generate polynomial features, train regression models, evaluate prediction accuracy, and visualize regression curves. The session also highlighted the importance of debugging visualization errors, reinforcing good programming and data analysis practices for developing reliable Machine Learning models.
