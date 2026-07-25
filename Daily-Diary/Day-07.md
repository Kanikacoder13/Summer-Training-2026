# Day 07 - Summer Training Report

# Pandas for Data Manipulation and Data Preprocessing

**Training Domain:** Artificial Intelligence & Machine Learning (AI & ML) using Python

---

## Objective

The objective of today's session was to understand the fundamentals of the Pandas library and its role in data manipulation, dataset inspection, data cleaning, filtering, aggregation, and preprocessing for Machine Learning applications.

---

## Topics Covered

### 1. Introduction to Pandas
- Introduction to the Pandas library.
- Importance of Pandas in AI & Machine Learning.
- Difference between Pandas Series and DataFrame.
- Creating Series and DataFrames manually.

### 2. Loading and Inspecting Datasets
- Reading datasets using `pd.read_csv()`.
- Creating mock CSV datasets using `io.StringIO`.
- Inspecting datasets using:
  - `head()`
  - `tail()`
  - `info()`
  - `describe()`
  - `shape`
  - `columns`
  - `index`
  - `dtypes`

### 3. Data Selection and Indexing
- Selecting single and multiple columns.
- Row and column selection using:
  - `loc[]`
  - `iloc[]`
- Label-based and positional indexing.
- Slicing DataFrames.
- Extracting specific records and subsets of data.

### 4. Boolean Indexing and Data Filtering
- Filtering records using Boolean conditions.
- Applying comparison operators for dataset filtering.
- Combining multiple conditions using:
  - `&` (AND)
  - `|` (OR)
  - `~` (NOT)
- Creating Boolean masks for data selection.

### 5. Handling Missing Values
- Identifying missing values using:
  - `isnull()`
  - `sum()`
- Filling missing values using `fillna()`.
- Replacing missing numerical values with the column mean.
- Removing missing records using `dropna()`.
- Importance of handling missing values before training Machine Learning models.

### 6. Grouping and Aggregation
- Introduction to `groupby()`.
- Grouping datasets based on categorical columns.
- Calculating aggregate statistics using:
  - `mean()`
  - `count()`
  - `sum()`
- Analyzing grouped customer and purchase data.

### 7. Student Dataset Practice
- Dataset loading and inspection.
- Boolean filtering of student records.
- Cleaning missing values.
- Grouping and summarizing student performance data.
- Computing average study hours, grades, and attendance based on pass status.

---

## Practical Activities Performed

During the practical session, I performed the following activities:

- Created Pandas Series and DataFrames.
- Loaded datasets using `pd.read_csv()` and `io.StringIO`.
- Inspected datasets using `head()`, `tail()`, `info()`, `describe()`, and dataset attributes.
- Selected rows and columns using `loc[]` and `iloc[]`.
- Performed column selection and DataFrame slicing.
- Filtered datasets using Boolean indexing and multiple logical conditions.
- Detected missing values using `isnull().sum()`.
- Filled missing values using `fillna()` and removed incomplete records using `dropna()`.
- Applied grouping and aggregation using `groupby()` to generate summary statistics.
- Solved hands-on exercises involving student evaluation datasets, including inspection, filtering, cleaning, and grouped analysis.

---

## Key Learning Outcomes

By the end of today's session, I was able to:

- Understand the fundamentals of the Pandas library.
- Create and manipulate Series and DataFrames.
- Load, inspect, and explore datasets efficiently.
- Select and filter data using indexing techniques.
- Handle missing values using appropriate preprocessing methods.
- Apply Boolean indexing for conditional data filtering.
- Perform grouping and aggregation to generate meaningful insights.
- Execute complete data preprocessing workflows required for Machine Learning applications.

---

## Conclusion

Today's session focused on developing practical skills in Pandas for data manipulation and preprocessing. Through extensive hands-on exercises, I learned how to load datasets, inspect data, filter records, handle missing values, perform grouping and aggregation, and prepare datasets for Machine Learning. These concepts form a fundamental part of every data analysis and AI & ML workflow.
