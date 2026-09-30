# 📊 Adult Census Income — Complete EDA Project

## 📌 Project Overview

This project is a **Complete Exploratory Data Analysis (EDA)** of the **Adult Census Income Dataset** using Python.

The project focuses on understanding the dataset, performing data cleaning, analyzing numerical and categorical features, identifying patterns and relationships, detecting potential outliers, and creating meaningful visualizations.

Both **Python data analysis libraries** and **automated EDA tools** were used to explore the dataset from different perspectives.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Understand the structure and characteristics of the dataset
* Inspect numerical and categorical variables
* Identify missing and null-like values
* Detect and remove duplicate records
* Perform data cleaning and preprocessing
* Calculate descriptive statistics
* Analyze individual variables
* Analyze relationships between variables
* Study income distribution
* Analyze demographic and work-related features
* Identify potential outliers
* Create different types of visualizations
* Perform automated exploratory data analysis
* Generate data profiling reports
* Explore the dataset interactively
* Extract meaningful insights from the data

---

## 🗂️ Dataset Information

The **Adult Census Income Dataset** contains information about individuals, including demographic characteristics, education, occupation, working hours, and income category.

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

# 🛠️ Technologies, Libraries & Tools

## Programming Language

* Python

## Python Libraries

* **Pandas** – Data loading, cleaning, manipulation and analysis
* **NumPy** – Numerical operations and data processing
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical and advanced visualizations

## Automated EDA Tools

### 🔹 AutoViz

Used for automatically generating different visualizations and exploring relationships and patterns in the dataset.

### 🔹 Sweetviz

Used to generate an automated EDA report containing dataset statistics, feature distributions, missing-value information and feature relationships.

### 🔹 D-Tale

Used for interactive exploration of the Pandas DataFrame, including filtering, sorting, statistics and column-level analysis.

### 🔹 YData

Used for automated data profiling and generating a detailed overview of the dataset, including distributions, missing values, correlations and other data-quality information.

## Environment

* Google Colab
* Jupyter Notebook

---

# 🔍 Complete EDA Process

The project follows a complete data analysis workflow.

## 1. 📥 Data Loading

The Adult Census Income CSV dataset was loaded into a Pandas DataFrame.

Basic data-loading operations were performed to make the dataset ready for analysis.

---

## 2. 🔎 Data Understanding

The structure and characteristics of the dataset were explored using:

```python
df.head()
df.tail()
df.shape
df.columns
df.info()
df.describe()
```

These operations helped understand:

* Number of rows and columns
* Column names
* Data types
* Numerical statistics
* Dataset structure

---

## 3. 🧹 Data Cleaning

The dataset was examined for data-quality issues.

The following activities were performed:

* Checked data types
* Identified missing values
* Identified null-like values
* Checked duplicate records
* Removed duplicate rows
* Prepared the data for further analysis

---

## 4. ❌ Missing Value Analysis

Missing and null-like values were analyzed across different columns.

Important columns containing missing values were identified and examined before continuing with the analysis.

This helped improve the quality and reliability of the analysis.

---

## 5. 🔁 Duplicate Analysis

Duplicate records were checked using Pandas.

```python
df.duplicated().sum()
```

Duplicate rows were identified and removed where appropriate.

This helped avoid repeated records affecting the analysis.

---

# 📊 6. Descriptive Statistics

Descriptive statistics were used to understand numerical variables.

Examples include:

* Mean
* Median
* Standard deviation
* Minimum
* Maximum
* Quartiles

The `describe()` function was used for numerical feature analysis.

---

# 📈 7. Univariate Analysis

Univariate analysis was performed to understand individual variables.

The following features were explored:

* Age
* Education
* Gender
* Income
* Hours per Week
* Workclass
* Occupation

Different charts were used to understand the distribution of individual features.

---

# 🔗 8. Bivariate Analysis

Bivariate analysis was performed to understand relationships between two variables.

Examples include:

* Age vs Hours per Week
* Education vs Income
* Gender vs Income
* Age vs Income
* Education vs Hours per Week

These relationships were explored using different visualizations.

---

# 📊 9. Multivariate Analysis

Multiple variables were analyzed together to understand more complex relationships.

Examples include:

* Gender + Income + Education
* Education + Income + Occupation
* Age + Hours per Week + Income
* Relationships between numerical variables

Seaborn visualizations and correlation analysis were used for multivariate exploration.

---

# 📉 10. Data Visualization

Different visualization techniques were used throughout the project.

## 📦 Box Plot

Used to understand numerical distributions and identify potential outliers.

---

## 🔵 Scatter Plot

Used to analyze relationships between two numerical variables.

**Example:**

`Age vs Hours per Week`

---

## 📊 Bar Chart

Used to compare values across different categories.

**Example:**

`Education Distribution`

---

## 📈 Line Plot

Used to visualize trends across ordered values or groups.

**Example:**

`Age Group Distribution`

---

## 🥧 Pie Chart

Used to understand proportions of different categories.

**Example:**

`Income Distribution`

---

## 📚 Count Plot

Used to compare the number of observations in categorical variables.

**Example:**

`Gender Distribution`

---

## 🟩 Stacked Bar Chart

Used to compare multiple categories within groups.

**Example:**

`Gender vs Income`

---

## 📊 Grouped Bar Chart

Used to compare categories side-by-side.

**Example:**

`Gender vs Income`

---

## 🔥 Heatmap

Used to visualize correlations between numerical variables.

The heatmap makes it easier to identify relationships between numerical features.

---

# 🤖 11. Automated EDA using AutoViz

**AutoViz** was used to automatically explore the dataset and generate multiple visualizations.

It helped analyze:

* Feature distributions
* Relationships between variables
* Numerical features
* Categorical features
* Patterns in the dataset

This provided a faster way to perform initial exploratory analysis.

---

# 📋 12. Automated EDA using Sweetviz

**Sweetviz** was used to generate an automated EDA report.

The report helped examine:

* Dataset summary
* Feature distributions
* Missing values
* Numerical variables
* Categorical variables
* Feature relationships
* Data statistics

The generated report provided a consolidated view of the dataset.

---

# 🖥️ 13. Interactive Analysis using D-Tale

**D-Tale** was used for interactive DataFrame exploration.

It helped with:

* Viewing the dataset interactively
* Sorting data
* Filtering records
* Exploring individual columns
* Viewing statistics
* Understanding data distributions

D-Tale provided an interactive way to inspect the Pandas DataFrame.

---

# 📑 14. Data Profiling using YData

**YData** was used to perform automated data profiling.

The profiling process helped analyze:

* Dataset structure
* Missing values
* Feature distributions
* Unique values
* Correlations
* Data-quality information
* Relationships between variables

This helped obtain a detailed overview of the dataset.

---

# 📌 15. Key Analysis Areas

The project explores the following areas:

* Age distribution
* Gender distribution
* Education distribution
* Income distribution
* Workclass distribution
* Occupation distribution
* Working-hours distribution
* Education vs Income
* Gender vs Income
* Age vs Hours per Week
* Numerical feature relationships
* Correlation between numerical variables
* Potential outliers
* Missing-value patterns
* Duplicate records

---

# 💡 16. Key Insights

The analysis was used to understand patterns related to:

* Demographic characteristics
* Education levels
* Employment categories
* Working hours
* Income categories
* Relationships between education and income
* Relationships between demographic features and income
* Distribution of numerical variables
* Potential outliers and unusual observations

The visualizations and automated EDA tools helped make these patterns easier to identify.

---

# 🧠 17. Skills Practiced

Through this project, I practiced:

### Python

* Python programming
* Data handling
* Data analysis

### Pandas

* DataFrame operations
* Data cleaning
* Missing-value analysis
* Duplicate handling
* Filtering
* Grouping
* Descriptive statistics

### NumPy

* Numerical operations
* Array manipulation
* Data processing

### Matplotlib

* Bar charts
* Line plots
* Scatter plots
* Pie charts
* Box plots
* Area charts
* Other visualizations

### Seaborn

* Count plots
* Box plots
* Scatter plots
* Heatmaps
* Statistical visualizations

### Automated EDA Tools

* AutoViz
* Sweetviz
* D-Tale
* YData

### Data Analytics

* Exploratory Data Analysis
* Data cleaning
* Data visualization
* Data profiling
* Univariate analysis
* Bivariate analysis
* Multivariate analysis
* Numerical and categorical analysis
* Insight generation

---

# 🔄 18. Data Analytics Workflow

```text
Raw Dataset
     ↓
Data Loading
     ↓
Data Understanding
     ↓
Data Cleaning
     ↓
Missing Value Analysis
     ↓
Duplicate Analysis
     ↓
Descriptive Statistics
     ↓
Univariate Analysis
     ↓
Bivariate Analysis
     ↓
Multivariate Analysis
     ↓
Data Visualization
     ↓
Automated EDA
     ↓
Data Profiling
     ↓
Insights & Conclusions
```

---

# 📁 Project Structure

```text
Adult-Census-Income-EDA/
│
├── adult.csv
│
├── EDA_Project_Tools.ipynb
│
└── README.md
```

---

# 🚀 Project Outcome

This project provided practical experience with the complete **Data Analytics and Exploratory Data Analysis workflow**.

Starting from a raw dataset, the project progressed through:

**Data Loading → Data Cleaning → Data Exploration → Visualization → Automated EDA → Data Profiling → Insights**

The project also provided hands-on experience with both traditional Python libraries and modern automated EDA tools such as **AutoViz, Sweetviz, D-Tale, and YData**.

---

# 🔮 Future Improvements

The project can be extended by:

* Performing deeper statistical analysis
* Creating additional feature-based visualizations
* Performing feature engineering
* Studying education, occupation and income relationships in greater detail
* Building an interactive dashboard using Power BI or Tableau
* Applying machine learning models to predict income categories
* Comparing different machine learning algorithms
* Performing advanced data preprocessing

---

# 👩‍💻 Author

**Harika Priyadharshini**

**B.Tech CSE | Aspiring Data Analyst**

---

⭐ **This project is part of my Data Analytics learning journey.**
