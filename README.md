# Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project is part of my **Data Analyst Internship - Task 5**.

The objective of this task is to perform **Exploratory Data Analysis (EDA)** on the Titanic dataset using Python to discover patterns, trends, relationships, and anomalies through statistical summaries and data visualization.

---

## 🎯 Objective

- Understand the dataset structure.
- Handle missing values.
- Explore numerical and categorical features.
- Visualize data distributions.
- Identify relationships between variables.
- Summarize key insights.

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset

**Dataset:** Titanic Dataset

The dataset contains information about 891 passengers, including:

- Passenger ID
- Survival Status
- Passenger Class
- Name
- Sex
- Age
- Number of Siblings/Spouses
- Number of Parents/Children
- Ticket Number
- Fare
- Cabin
- Embarked Port

---

## 🔧 Data Preprocessing

The following preprocessing steps were performed:

- Checked dataset information using `.info()`
- Generated statistical summary using `.describe()`
- Identified missing values
- Filled missing values in:
  - **Age** using the median
  - **Embarked** using the mode
- Dropped the **Cabin** column due to a high percentage of missing values

---

## 📊 Exploratory Data Analysis

The following visualizations were created:

- Histograms
- Count Plots
- Box Plots
- Scatter Plots
- Correlation Heatmap
- Pair Plot

These visualizations helped identify:

- Data distribution
- Outliers
- Correlations
- Passenger demographics
- Survival patterns

---

## 📈 Key Findings

- The dataset contains **891 passenger records**.
- Most passengers traveled in **Third Class**.
- Approximately **62%** of passengers did not survive.
- Most passengers were between **20 and 40 years old**.
- Ticket Fare is highly right-skewed with several outliers.
- Most passengers traveled without family members.
- Passenger Class and Fare show a moderate relationship.
- Female passengers had a higher survival rate than male passengers.
- First-class passengers had better survival rates compared to third-class passengers.

---

## 📚 Learning Outcomes

Through this project, I learned how to:

- Perform Exploratory Data Analysis (EDA)
- Handle missing data
- Create meaningful visualizations
- Interpret statistical summaries
- Identify patterns, trends, and outliers
- Summarize insights from data

---

## ✅ Conclusion

This project demonstrates the importance of Exploratory Data Analysis in understanding a dataset before applying machine learning or statistical modeling. EDA helps identify missing values, outliers, feature relationships, and meaningful insights that support data-driven decision-making.

---

## 👨‍💻 Author

**Kavi**

Data Analyst Internship - Task 5
