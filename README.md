# 📊 Exploratory Data Analysis — Student Performance Factors

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Student Performance Factors** dataset using Python.

The main purpose of this project is to analyze the dataset, understand its structure, identify patterns and trends, explore relationships between different factors, and determine the factors associated with students' exam performance.

The project uses statistical summaries and data visualizations to transform raw student data into meaningful insights.

---

## 🎯 Objectives

The main objectives of this project are:

* Understand the structure of the dataset.
* Perform basic data inspection and statistical analysis.
* Check for missing values and duplicate records.
* Analyze numerical and categorical variables.
* Identify patterns and trends in student performance.
* Study relationships between different factors and exam scores.
* Perform correlation analysis.
* Visualize important relationships using graphs.
* Identify factors associated with student academic performance.
* Present meaningful insights from the analysis.

---

## 📂 Dataset

The dataset used in this project is:

`StudentPerformanceFactors.csv`

The dataset contains **6,607 student records and 20 features** related to academic performance and other influencing factors.

### Dataset Features

* `Hours_Studied`
* `Attendance`
* `Parental_Involvement`
* `Access_to_Resources`
* `Extracurricular_Activities`
* `Sleep_Hours`
* `Previous_Scores`
* `Motivation_Level`
* `Internet_Access`
* `Tutoring_Sessions`
* `Family_Income`
* `Teacher_Quality`
* `School_Type`
* `Peer_Influence`
* `Physical_Activity`
* `Learning_Disabilities`
* `Parental_Education_Level`
* `Distance_from_Home`
* `Gender`
* `Exam_Score`

The main variable of interest in this analysis is **`Exam_Score`**.

---

## 🛠️ Technologies and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook / VS Code

---

## 📦 Installation

Install the required Python libraries using:

```bash
pip install pandas numpy matplotlib seaborn
```

---

## 🚀 Running the Project

1. Download or clone the project.
2. Make sure `StudentPerformanceFactors.csv` is in the project folder.
3. Open the EDA notebook in Jupyter Notebook or VS Code.
4. Run the cells sequentially from the beginning.
5. View the generated statistical summaries and visualizations.

The dataset can be loaded using:

```python
import pandas as pd

df = pd.read_csv("StudentPerformanceFactors.csv")
```

---

## 🔍 EDA Process

The project follows a structured Exploratory Data Analysis workflow.

### 1. Data Understanding

The dataset is initially explored using functions such as:

```python
df.head()
df.tail()
df.shape
df.columns
df.info()
df.dtypes
df.describe()
df.nunique()
```

These operations help understand the size, structure, data types, and statistical characteristics of the dataset.

### 2. Data Cleaning

The dataset is checked for:

* Missing values
* Duplicate records
* Incorrect or inconsistent data
* Data types

Missing values are examined using:

```python
df.isnull().sum()
```

Duplicate records are examined using:

```python
df.duplicated().sum()
```

### 3. Univariate Analysis

Individual variables are analyzed to understand their distributions.

Examples include:

* Exam Score distribution
* Hours Studied distribution
* Attendance distribution
* Gender distribution
* Boxplots for detecting potential outliers

### 4. Bivariate Analysis

Relationships between two variables are explored.

Important comparisons include:

* Hours Studied vs Exam Score
* Attendance vs Exam Score
* Previous Scores vs Exam Score
* Sleep Hours vs Exam Score
* Gender vs Exam Score
* Teacher Quality vs Exam Score
* Parental Involvement vs Exam Score
* Family Income vs Exam Score
* Internet Access vs Exam Score
* Motivation Level vs Exam Score

### 5. Correlation Analysis

A correlation matrix is generated for numerical variables to examine linear relationships between them.

A correlation heatmap is used to make these relationships easier to understand visually.

Special attention is given to the correlation of numerical variables with `Exam_Score`.

> **Note:** Correlation indicates association and does not by itself establish causation.

### 6. Group Analysis

Students are grouped according to categorical factors to compare their average exam performance.

Examples include:

* Average Exam Score by Gender
* Average Exam Score by Motivation Level
* Average Exam Score by Parental Involvement
* Average Exam Score by Teacher Quality
* Average Exam Score by Family Income

---

## 📈 Visualizations

The project uses several visualization techniques, including:

* Histograms
* Count plots
* Boxplots
* Scatter plots
* Correlation heatmap
* Pair plots

These visualizations make it easier to identify distributions, relationships, trends, and potential outliers in the dataset.

---

## 🔑 Key Analysis Areas

The analysis focuses on understanding how different factors are associated with student exam performance, particularly:

**Academic Factors**

* Hours Studied
* Previous Scores
* Attendance
* Tutoring Sessions

**Personal Factors**

* Sleep Hours
* Motivation Level
* Physical Activity
* Learning Disabilities

**Family Factors**

* Parental Involvement
* Family Income
* Parental Education Level

**Educational and Environmental Factors**

* Teacher Quality
* Access to Resources
* Internet Access
* School Type
* Peer Influence
* Distance from Home

---

## 💡 Key Insights

The EDA helps reveal:

* The overall distribution of student exam scores.
* Relationships between study habits and academic performance.
* The association between attendance and exam scores.
* How previous academic performance relates to current exam performance.
* Differences in exam performance across categorical factors.
* Potential outliers in numerical variables.
* Numerical variables that have stronger or weaker correlations with exam scores.

The exact findings should be interpreted from the statistical outputs and visualizations generated by the notebook.

---

## 📝 Conclusion

This project demonstrates the use of **Exploratory Data Analysis** to understand student performance data.

Using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn, the dataset was inspected, cleaned, summarized, and visualized. Different academic, personal, family, and environmental factors were explored to understand their relationships with student exam performance.

The project demonstrates how statistical analysis and data visualization can be used to discover meaningful patterns and relationships within a dataset and provides a foundation for further data analysis or machine-learning applications.

---

## 📁 Project Structure

```text
Student-Performance-EDA/
│
├── StudentPerformanceFactors.csv
├── Student_Performance_EDA.ipynb
└── README.md
```

---

## 👩‍💻 Project Type

**Exploratory Data Analysis (EDA)**

**Domain:** Education / Student Performance Analysis

**Language:** Python
