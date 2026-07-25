# Day 05 - Summer Training Report

# NumPy Fundamentals and Essential Operations for AI & Machine Learning

**Training Domain:** Artificial Intelligence & Machine Learning (AI & ML) using Python

---

## Objective

The objective of today's session was to understand the fundamentals of NumPy and its importance in AI & Machine Learning. The session focused on efficient array operations, vectorization, indexing, slicing, broadcasting, data filtering, statistical analysis, reshaping, matrix operations, and practical data preprocessing techniques used in machine learning.

---

## Topics Covered

### 1. Introduction to NumPy
- Introduction to NumPy (Numerical Python).
- Importance of NumPy in AI & Machine Learning.
- Comparison between Python Lists and NumPy Arrays.
- Advantages of contiguous memory allocation and faster computations.

### 2. Creating NumPy Arrays
- Creating 1D and 2D arrays using `np.array()`.
- Creating arrays using:
  - `np.zeros()`
  - `np.ones()`
  - `np.arange()`
- Array attributes:
  - `shape`
  - `dtype`
  - `ndim`

### 3. Vectorization
- Performing mathematical operations without using loops.
- Element-wise arithmetic operations.
- Performance comparison between Python loops and NumPy vectorization.
- Benefits of vectorization in large datasets.

### 4. Array Indexing and Slicing
- Accessing individual elements.
- Row-wise and column-wise indexing.
- Array slicing.
- Extracting features (`X`) and labels (`y`) from datasets.
- Working with multidimensional arrays.

### 5. Boolean Indexing and Data Filtering
- Boolean masking.
- Filtering data based on conditions.
- Selecting required elements from arrays.
- Data cleaning using Boolean masks.
- Replacing invalid values using `np.where()`.

### 6. Views and Copies
- Difference between Views and Copies.
- Memory sharing in NumPy arrays.
- Creating independent copies using `.copy()`.

### 7. Broadcasting
- Introduction to Broadcasting.
- Broadcasting rules.
- Scalar and array broadcasting.
- Broadcasting with matrices.
- Standardizing datasets using broadcasting.

### 8. Statistical Operations
- Mean using `np.mean()`
- Median using `np.median()`
- Standard Deviation using `np.std()`
- Column-wise and row-wise statistical calculations.

### 9. Reshaping and Flattening
- Reshaping arrays using `reshape()`.
- Flattening multidimensional arrays using `flatten()`.
- Importance of reshaping for AI/ML model inputs.

### 10. Matrix Operations
- Matrix multiplication using:
  - `np.dot()`
  - `@` operator
- Neural network input-weight multiplication.

---

## Practical Activities Performed

During the practical session, I performed the following activities:

- Created 1D and 2D NumPy arrays.
- Practiced array initialization using `zeros()`, `ones()`, and `arange()`.
- Compared the execution speed of Python loops with NumPy vectorized operations.
- Performed element-wise arithmetic operations on arrays.
- Implemented indexing and slicing on one-dimensional and two-dimensional arrays.
- Extracted feature matrices (`X`) and target labels (`y`) from sample datasets.
- Filtered arrays using Boolean indexing.
- Cleaned datasets using Boolean masks and `np.where()`.
- Explored the difference between array Views and Copies using `.copy()`.
- Applied broadcasting for arithmetic operations and feature standardization.
- Calculated statistical measures including mean, median, and standard deviation.
- Reshaped and flattened arrays for machine learning data preparation.
- Performed matrix multiplication using `np.dot()` and the `@` operator.
- Solved practical exercises including:
  - Celsius to Fahrenheit conversion using vectorization.
  - Salary filtering and data cleaning.
  - Matrix slicing operations.
  - Safe copy creation using `.copy()`.
  - Feature and label extraction from datasets.
  - Customer age outlier correction using `np.where()`.
  - Feature normalization using broadcasting.

---

## Key Learning Outcomes

By the end of today's session, I was able to:

- Understand the advantages of NumPy over Python lists.
- Create and manipulate one-dimensional and two-dimensional arrays.
- Perform efficient mathematical operations using vectorization.
- Apply indexing and slicing techniques for dataset manipulation.
- Clean and filter datasets using Boolean indexing and `np.where()`.
- Differentiate between array Views and Copies.
- Use broadcasting for efficient array computations.
- Calculate statistical summaries for datasets.
- Reshape and flatten arrays for AI & ML applications.
- Perform matrix multiplication and basic data preprocessing using NumPy.

---

## Conclusion

Today's session introduced NumPy as a powerful library for numerical computing and data processing in Artificial Intelligence and Machine Learning. Through extensive hands-on exercises, I learned how to efficiently create, manipulate, filter, reshape, and analyze datasets using NumPy. The practical implementation of vectorization, broadcasting, statistical operations, and matrix manipulation provided a strong foundation for handling real-world AI & ML datasets.
