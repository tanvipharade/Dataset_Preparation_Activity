# Dataset_Preparation_Activity
# 📊 Activity 1: Dataset Preparation

## Student Performance Dataset – Data Cleaning and Exploratory Data Analysis

### 📌 Project Information
- **Activity:** Activity 1 – Dataset Preparation
- **Unit:** Unit I – Foundations & Data Preparation
- **Domain:** Education
- **Dataset:** Student Performance Dataset (Mathematics)
- **Programming Language:** Python
- **Platform:** Google Colab / Jupyter Notebook

---

## 🎯 Objective

The objective of this activity is to inspect a dataset, identify data-quality issues, handle missing values, perform basic Exploratory Data Analysis (EDA), and prepare a cleaned dataset for future Machine Learning workflows.

No prediction model is trained in this activity.

## 📂 Dataset Description

The Student Performance Dataset contains information about students in Portuguese secondary schools.

It includes information about:
- Student demographics
- Family background
- Study habits
- School attendance
- Academic performance

**Dataset Source:** UCI Machine Learning Repository

**Dataset Link:** https://archive.ics.uci.edu/dataset/320/student+performance

**File Used:** `student-mat.csv`

**Original Dataset Dimensions:** 395 rows × 33 columns.

### Important Features
| Feature | Description |
|---|---|
| school | Student's school |
| sex | Student's gender |
| age | Student's age |
| studytime | Weekly study time |
| failures | Number of past class failures |
| absences | Number of school absences |
| G1 | First-period grade |
| G2 | Second-period grade |
| G3 | Final mathematics grade |

## 🛠️ Technologies and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## ⚙️ Activities Performed

### 1. Dataset Selection
Selected the Student Performance dataset from the UCI Machine Learning Repository.

### 2. Dataset Loading and Inspection
- Loaded the CSV dataset using Pandas.
- Displayed the first and last five records.
- Checked rows, columns and data types.

### 3. Data Types and Statistics
- Identified numerical and categorical columns.
- Calculated descriptive statistics.
- Identified `G3` as a possible future prediction target.

### 4. Missing Value Detection
- Checked missing values in all columns.
- Calculated missing-value counts and percentages.
- Applied imputation only where required.

### 5. Data Cleaning
- Checked duplicate records.
- Removed exact duplicate rows if present.
- Checked inconsistent category formatting.

### 6. Exploratory Data Analysis (EDA)
- Calculated summary statistics.
- Generated frequency counts.
- Created histograms, box plots and scatter plots.
- Observed patterns in student performance.

### 7. Categorical Encoding
Applied One-Hot Encoding to nominal categorical features.

### 8. Numerical Feature Scaling
Applied StandardScaler to suitable numerical input features.

### 9. Final Dataset Preparation
- Verified missing values and duplicates.
- Checked final dataset dimensions.
- Exported the prepared dataset as a CSV file.

## 📊 Visualizations

The notebook includes:
1. Distribution of Final Mathematics Grades (G3).
2. Final Grade by Weekly Study Time.
3. School Absences vs Final Mathematics Grade.

## 📁 Project Structure

```text
Activity-1-Dataset-Preparation/
│
├── dataset/
│   ├── student-mat.csv
│   └── student_performance_prepared.csv
│
├── notebook/
│   └── Activity1_Student_Performance.ipynb
│
├── report/
│   └── Activity1_Student_Performance_Report.pdf
│
├── README.md
└── requirements.txt
```

## ▶️ How to Run the Project

1. Download or clone this repository.
2. Open the Jupyter Notebook in Google Colab or Jupyter Notebook.
3. Install the required Python libraries.
4. Run all notebook cells sequentially.
5. View the data analysis tables and visualizations.
6. Download the final prepared CSV dataset.

## 📌 Conclusion

This activity demonstrates the basic data preparation workflow using Python. The dataset was inspected, data types were identified, missing values and duplicates were checked, and exploratory data analysis was performed.

Categorical features were encoded using One-Hot Encoding, and suitable numerical features were standardised using StandardScaler.

Finally, the prepared dataset was saved as a separate CSV file for future Machine Learning applications.

## 📚 References

Cortez, P. (2008). Student Performance Dataset. UCI Machine Learning Repository.

Dataset Link: https://archive.ics.uci.edu/dataset/320/student+performance

---

**Project Status:** Dataset Preparation Activity

**Note:** This project focuses on data preparation and exploratory data analysis. No Machine Learning prediction model is implemented.
