## Project Overview

The analysis includes data inspection, handling missing values, visualization, and statistical summaries to better understand the dataset and prepare it for further machine learning or analytical tasks.

---

## Objectives

* Understand the dataset structure
* Analyze **categorical and numerical variables**
* Detect **missing values (null values)**
* Identify **outliers**
* Visualize relationships between variables
* Generate insights from the data
* Feature Engineering

---

## Dataset

The dataset contains user engagement information such as likes and activity metrics.

Key aspects analyzed:

* Distribution of likes and engagement metrics
* User interaction patterns
* Extreme values (outliers)
* Missing values within the dataset

---

## Analysis Steps

### 1. General Overview

* Dataset shape
* Data types
* Summary statistics
* Unique values

### 2. Categorical Variable Analysis

* Frequency distributions
* Category counts
* Category proportions

### 3. Numerical Variable Analysis

* Mean, median, quantiles
* Distribution analysis
* Detection of skewness

### 4. Missing Value Analysis

* Identification of null values
* Examination of missing data patterns

### 5. Data Visualization

Several visualizations were created to better understand the dataset:

* Scatter plots
* Box plots
* Count plots
* Distribution plots
* Correlation heatmaps

### 6. Outlier Detection

Outliers were analyzed using statistical techniques and visualization methods such as boxplots.


### 7. Feature Engineering

To prepare the dataset for potential machine learning tasks, several **encoding techniques** were applied to categorical variables.

Encoding helps convert categorical data into numerical format so that machine learning algorithms can process it effectively.

Techniques used:

* **Label Encoding** – converting categories into numeric labels
* **One-Hot Encoding** – creating binary variables for categorical features
* **Binary Encoding** – handling variables with two unique categories

These transformations improve the usability of the dataset for further modeling and analysis.

---

## Key Insights

* Most users receive **low to medium engagement levels**.
* The data distribution is **not perfectly normal**.
* Some users receive **extremely high likes**, indicating strong outliers.
* Engagement metrics show **significant variability across users**.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Conclusion

This exploratory data analysis provides insights into user engagement patterns and highlights the importance of handling missing values and outliers before applying machine learning models.