# Data-Analytics-Projects
A collection of my Data Analytics learning journey, including Python, SQL, Pandas, NumPy, Matplotlib, Seaborn, data analysis projects, and practical exercises.
# 📊 Adult Census Income Data Analysis

## 📌 Project Overview

This project is an **Exploratory Data Analysis (EDA)** of the **Adult Census Income Dataset** using Python.

The project focuses on understanding the dataset, performing basic data cleaning, analyzing numerical and categorical features, and creating visualizations to identify patterns and relationships in the data.

The analysis is performed using **Pandas, NumPy, Matplotlib, and Seaborn**.

---

## 🎯 Project Objectives

* Understand the structure of the Adult dataset
* Explore numerical and categorical variables
* Check for missing values
* Identify and remove duplicate records
* Analyze different features using descriptive statistics
* Study income distribution
* Compare income with demographic and work-related features
* Visualize patterns and relationships using different charts

---

## 🗂️ Dataset Information

The dataset contains information related to individuals, including their age, education, occupation, working hours, and income category.

### Dataset Columns

| No. | Column Name      | Description                           |
| --: | ---------------- | ------------------------------------- |
|   1 | `Age`            | Age of the individual                 |
|   2 | `Workclass`      | Type of employment                    |
|   3 | `Final Weight`   | Census sampling weight                |
|   4 | `Education`      | Education level                       |
|   5 | `EducationNum`   | Numerical representation of education |
|   6 | `Marital Status` | Marital status                        |
|   7 | `Occupation`     | Type of occupation                    |
|   8 | `Relationship`   | Relationship status                   |
|   9 | `Race`           | Race category                         |
|  10 | `Gender`         | Gender                                |
|  11 | `Capital Gain`   | Capital gain amount                   |
|  12 | `capital loss`   | Capital loss amount                   |
|  13 | `Hours per Week` | Number of hours worked per week       |
|  14 | `Native Country` | Country of origin                     |
|  15 | `Income`         | Income category                       |

---

## 🛠️ Technologies & Libraries

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn

### Environment

* Google Colab


---

## 🔍 Data Analysis Process

The project follows these major steps:

### 1. Data Loading

Loaded the Adult CSV dataset into a Pandas DataFrame.

### 2. Data Understanding

Performed:

* `head()`
* `tail()`
* `shape`
* `columns`
* `info()`
* `describe()`

to understand the dataset structure.

### 3. Missing Value Analysis

Checked the dataset for missing or null-like values in different columns.

### 4. Duplicate Analysis

Checked for duplicate records and removed duplicate rows from the dataset.

### 5. Exploratory Data Analysis

Analyzed individual columns and relationships between different variables.

---

## 📊 Data Visualizations

Different charts were created to understand the dataset:

### 📦 Box Plot

Used to understand the distribution of numerical data and identify potential outliers.

### 🔵 Scatter Plot

Used to study the relationship between two numerical variables.

Example:

**Age vs Hours per Week**

### 📊 Bar Chart

Used to compare values across categories.

Example:

**Education Distribution**

### 📈 Line Plot

Used to visualize changes across ordered groups.

Example:

**Age Group Distribution**

### 🥧 Pie Chart

Used to understand the proportion of income categories.

Example:

**Income Distribution**

### 📚 Count Plot

Used to compare the number of observations in categorical variables.

Example:

**Gender Distribution**

### 🟩 Stacked Bar Chart

Used to compare income categories within gender groups.

Example:

**Gender vs Income**

### 📊 Grouped Bar Chart

Used to compare income categories side-by-side for different gender groups.

Example:

**Gender vs Income**

### 🔥 Heatmap

Used to visualize relationships between numerical variables.

---

## 📈 Key Analysis Areas

The project explores relationships such as:

* Age distribution
* Gender distribution
* Education distribution
* Income distribution
* Age vs Hours per Week
* Gender vs Income
* Education vs Income
* Numerical feature relationships
* Distribution of working hours
* Potential outliers in numerical features

---

## 📁 Project Structure

```text
Adult-Dataset-Analysis/
│
├── adult.csv
│
├── Adult_Data_Analysis.ipynb
│
└── README.md
```

---

## 💡 Skills Practiced

Through this project, I practiced:

* Data loading
* Data cleaning
* Data inspection
* Handling duplicate records
* Working with numerical and categorical data
* Pandas DataFrame operations
* Data visualization
* Exploratory Data Analysis
* Creating charts using Matplotlib
* Creating statistical visualizations using Seaborn

---

## 🚀 Project Outcome

This project helped me understand the basic **Data Analytics workflow**, starting from raw data and progressing through data cleaning, exploration, and visualization.

It also provided practical experience in using Python libraries to analyze a real-world dataset.

---

## 👩‍💻 Author

**Harika Priyadharshini**

**B.Tech CSE | Aspiring Data Analyst**

---

## ⭐ Future Improvements

* Perform deeper statistical analysis
* Create more feature-based visualizations
* Analyze relationships between education, occupation, and income
* Build an interactive dashboard
* Perform further data preprocessing and feature engineering
