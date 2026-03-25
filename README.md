# Student Dropout Analysis

## Project Overview
This project focuses on analyzing student data to identify key factors associated with dropout. Using Exploratory Data Analysis (EDA), statistical testing, and feature engineering, the goal is to understand patterns and build meaningful insights.

---

## Objectives
- Identify factors influencing student dropout
- Analyze academic, behavioral, and demographic variables
- Perform statistical testing to validate insights
- Create meaningful features for future modeling

---

## Dataset Information
- Source: Kaggle (Student Dropout Dataset)
- Rows: 10,000
- Columns: 19 (expanded to 22 with feature engineering)
- Target Variable: Dropout


##  Project Structure

eda-project/
│
├── data/
│ ├── raw/ # Original dataset
│ ├── interim/ # Cleaned dataset (Day 2)
│ └── processed/ # Final dataset (Day 4)
│
├── notebooks/
│ ├── 01_data_overview.ipynb
│ ├── 02_cleaning_preprocessing.ipynb
│ ├── 03_univariate_bivariate_eda.ipynb
│ └── 04_stats_time_features_final_insights.ipynb
│
├── reports/
│ └── figures/ # Saved visualizations
│
└── README.md



---

##  Key Steps Performed

### 1. Data Overview
- Understanding dataset structure
- Checking data types and distributions
- Identifying missing values

### 2. Data Cleaning
- Handling missing values
- Fixing inconsistencies

### 3. Exploratory Data Analysis (EDA)
- Univariate analysis (distributions, counts)
- Bivariate analysis (relationships with dropout)
- Correlation analysis (heatmap)

### 4. Statistical Testing
- **T-test**: GPA vs Dropout
- **ANOVA**: GPA across departments
- **Chi-square**: Categorical relationships

### 5. Feature Engineering
- Created new features like:
  - CGPA_Improvement
  - Study Efficiency
  - Academic_Habits_Score

---

##  Key Insights

- Dropout is strongly influenced by academic performance, especially GPA  
- Higher stress levels are associated with increased dropout risk  
- Attendance has a mild impact on dropout      
- Dropout rates are consistent across semesters  
- Academic factors dominate over demographic factors  

---

## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

---

## How to Run This Project

1. Clone the repository:
```bash
git clone https://github.com/aathikaop/EDA-PROJECT.git
