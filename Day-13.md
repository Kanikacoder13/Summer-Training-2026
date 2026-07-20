# Day 13 - Summer Training Report

# Linear Regression for House Price Prediction

**Training Domain:** Artificial Intelligence & Machine Learning (AI & ML) using Python

---

## Objective

The objective of today's session was to understand the fundamentals of Linear Regression and its application in predicting house prices. The session focused on dataset preparation, train-test splitting, building Simple and Multiple Linear Regression models, making predictions, visualizing results, and evaluating model performance using regression metrics.

---

## Topics Covered

### 1. Introduction to Linear Regression
- Understanding Linear Regression as a supervised Machine Learning algorithm.
- Predicting continuous numerical values.
- House Price Prediction as a regression problem.
- Difference between Simple Linear Regression and Multiple Linear Regression.

### 2. Dataset Preparation
- Loading the preprocessed House Price dataset using Pandas.
- Selecting input features (X) and target variable (y).
- Understanding independent and dependent variables.

### 3. Train-Test Split
- Splitting the dataset into Training and Testing sets.
- Using an 80:20 train-test ratio.
- Importance of training on known data and testing on unseen data.
- Implementing `train_test_split()` from Scikit-learn.

### 4. Simple Linear Regression
- Building a Simple Linear Regression model using **Scaled_size** as the predictor.
- Training the model using `LinearRegression()`.
- Understanding:
  - Coefficient (Slope)
  - Intercept
- Formulating the regression equation.
- Predicting house prices using the trained model.

### 5. Regression Visualization
- Plotting the best-fit regression line.
- Comparing actual house prices with predicted values.
- Visualizing prediction results using Scatter Plot and Regression Line.

### 6. Multiple Linear Regression
- Training a model using multiple input features.
- Using features such as:
  - Bedrooms
  - Bathrooms
  - Scaled House Size
  - Floors
  - Waterfront
  - Living Area
  - House Condition
  - Location Categories
- Comparing Simple and Multiple Linear Regression models.

### 7. Custom House Price Prediction
- Creating a custom house record.
- Predicting the price of a new house using the trained Multiple Linear Regression model.
- Understanding how feature values influence predictions.

### 8. Model Evaluation
- Evaluating regression models using:
  - Mean Absolute Error (MAE)
  - R² Score (Coefficient of Determination)
- Comparing the performance of Simple and Multiple Linear Regression models.
- Understanding the impact of additional features on prediction accuracy.

---

## Practical Activities Performed

During the practical session, I performed the following activities:

- Installed and imported the required Scikit-learn libraries.
- Loaded the preprocessed House Price dataset.
- Selected input features and target values for model training.
- Split the dataset into training and testing sets using an 80:20 ratio.
- Trained a Simple Linear Regression model using house size as the predictor.
- Retrieved the regression coefficient and intercept.
- Generated predictions for the testing dataset.
- Visualized the regression line with actual house price data.
- Built a Multiple Linear Regression model using all available features.
- Compared predictions from both regression models.
- Predicted the price of a custom house using user-defined feature values.
- Evaluated both models using MAE and R² Score.
- Compared the accuracy of Simple and Multiple Linear Regression models.

---

## Key Learning Outcomes

By the end of today's session, I was able to:

- Understand the working principle of Linear Regression.
- Differentiate between Simple and Multiple Linear Regression.
- Prepare datasets for supervised Machine Learning.
- Perform train-test splitting using Scikit-learn.
- Train Linear Regression models for numerical prediction.
- Interpret regression coefficients and intercept values.
- Visualize regression results using graphs.
- Predict outcomes for new data using trained models.
- Evaluate regression models using MAE and R² Score.
- Analyze how additional features improve prediction performance.

---

## Conclusion

Today's session introduced Linear Regression as one of the fundamental supervised Machine Learning algorithms used for predicting continuous values. Through practical implementation on a real-world House Price dataset, I learned how to prepare data, train regression models, generate predictions, visualize results, and evaluate model performance. The comparison between Simple and Multiple Linear Regression demonstrated how incorporating multiple relevant features can improve prediction accuracy and build more effective Machine Learning models.
