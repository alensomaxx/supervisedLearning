# Supervised Learning Revision Notes

## Types of Data

- **Structured Data:** Organized as rows and columns.
- **Unstructured Data:** Every entry has a unique identifier for data management.

### Examples of Unstructured Data Platforms
*(User to provide examples)*

### Querying Data on Structured Data Patterns
*(User to provide details)*

---

## Feature Engineering

> **Key Definition:** The process of using domain knowledge to extract features from raw data. These features can be used to improve the performance of machine learning models.

### Approaches / Methods

- **Transformation:**
  - Log Transformation
  - Box-Cox Transformation
  - Square Root Transformation
- **Imputation:**
  - Handling missing values.
- **Scaling:**
  - Min-Max Scaling
  - Standard Scaling
- **Encoding:**
  - Label Encoding
  - One-Hot Encoding

---

## Data Pre-Processing

- **Handling Outliers:**
  - Winsorization
- All techniques from **Feature Engineering** also apply here.

> **Note:** Include theory details and coding snippets with proper syntax for each pre-processing step.

---

## Data Visualization

- Simple, direct application of **Matplotlib** and **Seaborn** libraries.
- **Common Plots:**
  - Line Plot
  - Scatter Plot
  - Bar Graph
  - Heatmap
- Refer to data visualization techniques in the classification and linear regression notebooks.

### Importance of Seaborn Library

- Accomplishes data analytics tasks with less code.
- **Example:** FMRI dataset and the lineplot example.

---

## Linear Regression

- **Implementation Example:** TV marketing and sales dataset.
- **Evaluation Metrics:**
  - **MSE (Mean Squared Error):** For both training and testing sets.
  - **R-squared (R²) Score:** The coefficient of regression. Should be close to 1 (higher is better).

> "Coefficient of regression is called as R^2 Score" from best-fit score.

---

## Statistical Outcomes: Goals and Objectives

### Regression Metrics

- **R² Score:** Measures the proportion of the variance in the dependent variable that is predictable from the independent variable(s).
- **MSE (Mean Squared Error):** The average squared difference between the estimated values and the actual value.
- **MAE (Mean Absolute Error):** The average of the absolute differences between the predicted and actual values.

### Classification Metrics

- **Accuracy:** The ratio of correctly predicted instances to the total instances.
- **Precision:** The ratio of correctly predicted positive observations to the total predicted positive observations.
- **Recall (Sensitivity):** The ratio of correctly predicted positive observations to all observations in the actual class.
- **Specificity:** The ratio of correctly predicted negative observations to all observations in the actual negative class.
- **F1-Score:** The weighted average of Precision and Recall.


### Types of Supervised Machine Learning


Define the following:

SUPERVISED MACHINE LEARNING 
REGRESSION ALGORITHMS
LINEAR REGRESSION ALGORITHM
CLASSIFICATION ALGOROTHMS
LOGISTIC REGRESSION
NAIVE BAYES ALGORITHM 
DECISION TREES ALGORITHM
SUPPORT VECTOR MACHINE ALGORITHM
KNN (default value of K = 3)


WHAT WE NEED 
DEFINITON + Example + practical Implementation (6 steps)

WHAT NOT NEED TO BE DONE 
OPTIMIZATION
VERY DEEP THEORTIC DETAILS
GOAL: is Proof of concept (POC) by NOV 19th
THE FIRST ALGORITHM cannot be claimed as the best algorithm 
Multiple algotihm has to be tested and performace has to be compared before shortlisting 
the best performing algorithm


