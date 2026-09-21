# Student Performance Prediction

## 📌 Project Overview

Student Performance Prediction is a supervised machine learning project that analyzes student-related academic and personal factors to predict student performance.

The project uses a student performance dataset containing information such as study time, previous failures, family background, attendance-related information, and academic grades.

The main purpose of this project is to understand how machine learning can be applied to educational data and identify patterns that may be useful for predicting student performance.

---

## 🎯 Objectives

The main objectives of this project are:

- To analyze the student performance dataset.
- To understand the different attributes present in the dataset.
- To perform data preprocessing.
- To identify patterns and relationships between different student-related factors.
- To apply supervised machine learning techniques for prediction.
- To evaluate the performance of the trained model.
- To use the trained model for predicting student performance.

---

## 📊 Dataset

The dataset contains:

- **395 records**
- **33 variables**

### Important Variables

| Variable | Description |
|----------|-------------|
| `school` | Student's school |
| `sex` | Student's gender |
| `age` | Student's age |
| `address` | Type of home address |
| `famsize` | Family size |
| `Pstatus` | Parent's cohabitation status |
| `Medu` | Mother's education |
| `Fedu` | Father's education |
| `Mjob` | Mother's occupation |
| `Fjob` | Father's occupation |
| `studytime` | Weekly study time |
| `failures` | Number of past class failures |
| `schoolsup` | Extra educational support |
| `famsup` | Family educational support |
| `internet` | Internet access |
| `famrel` | Family relationship quality |
| `freetime` | Free time after school |
| `goout` | Going out with friends |
| `health` | Current health status |
| `absences` | Number of school absences |
| `G1` | First-period grade |
| `G2` | Second-period grade |
| `G3` | Final grade |

The dataset contains both numerical and categorical variables.

---

## 🔧 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## ⚙️ Project Workflow

The project follows these major steps:

### 1. Data Loading

The dataset is loaded into a Pandas DataFrame for analysis.

### 2. Data Understanding

The dataset is examined using functions such as:

```python
df.head()
df.info()
df.shape
df.isnull().sum()
