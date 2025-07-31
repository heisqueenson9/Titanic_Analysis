# 🚢 Titanic Survival Data Analysis Project

## 📘 Table of Contents
1. [Introduction](#introduction)
2. [Project Objectives](#project-objectives)
3. [Dataset Overview](#dataset-overview)
4. [Tools & Technologies](#tools--technologies)
5. [Data Cleaning & Preparation](#data-cleaning--preparation)
6. [Exploratory Data Analysis](#exploratory-data-analysis)
7. [Insights & Findings](#insights--findings)
8. [Visual Analysis (Power BI)](#visual-analysis-power-bi)
9. [Conclusion](#conclusion)
10. [References](#references)

---

## ✳️ Introduction

The sinking of the RMS Titanic in April 1912 is one of the most infamous maritime disasters in history. The tragedy, which led to the deaths of over 1,500 people, has since become a subject of extensive historical, social, and data-driven study. In this project, we aim to explore and analyze the Titanic passenger dataset using both Python (Jupyter Notebook) and Power BI. Our goal is to uncover patterns and factors that contributed to passenger survival.

The dataset includes various attributes of passengers, such as age, gender, ticket class, fare paid, and whether or not they survived. By applying basic data science techniques such as data cleaning, exploration, visualization, and interpretation, we aim to answer questions like: Were women more likely to survive than men? Did age or class matter? Could we predict survival using these features?

This project is designed to guide absolute beginners through the data analysis workflow—from raw CSV files to visual dashboards and final documentation on GitHub. Whether you're new to Python, Power BI, or GitHub, this project provides a comprehensive walkthrough.

---

## 🎯 Project Objectives

- Load and clean the Titanic dataset.
- Perform exploratory data analysis using Python.
- Create visual dashboards in Power BI to support insights.
- Identify significant factors that influenced survival.
- Upload the cleaned dataset and analysis to GitHub.
- Document the entire process using Markdown.

---

## 🗃️ Dataset Overview

The dataset used in this project is a cleaned version of the original Titanic dataset from [Kaggle’s Titanic Competition](https://www.kaggle.com/competitions/titanic/data). It contains 418 rows and the following key columns:

- Survived: Whether the passenger survived (1) or not (0)
- Pclass: Ticket class (1 = upper, 2 = middle, 3 = lower)
- Sex: Gender of the passenger
- Age: Age in years
- SibSp: Number of siblings/spouses aboard
- Parch: Number of parents/children aboard
- Fare: Amount paid for the ticket
- Embarked: Port of embarkation (S, C, Q)

---

## 🛠 Tools & Technologies

- Python (Jupyter Notebook) – Data loading, cleaning, and analysis
- Pandas – For manipulating tabular data
- Seaborn & Matplotlib – For visualizations
- Power BI Desktop – For dashboard-style visual analysis
- Git & GitHub – For version control and sharing the project
- Markdown – For project documentation

---

## 🧹 Data Cleaning & Preparation

The raw dataset contained missing values in key columns like Age, Fare, and Cabin. Here’s how cleaning was done:

- Dropped the Cabin column due to over 70% missing data.
- Imputed missing Age and Fare values with the median.
- Encoded categorical variables: Sex (male=0, female=1), Embarked (S=0, C=1, Q=2).
- Dropped PassengerId, Name, and Ticket for simplicity.

This cleaned dataset (`titanic_cleaned.csv`) was then used for analysis and visualization.

---

## 🔍 Exploratory Data Analysis

With the cleaned data, we explored several relationships:

- Survival vs Gender: Significantly more women survived than men.
- Survival vs Class: Higher classes had better survival rates.
- Age Distribution: Younger children showed higher survival rates.
- Correlation Heatmap: Revealed moderate relationship between class and survival.

These findings were visualized using Seaborn’s countplots and histograms in the Jupyter Notebook.

---

## 📊 Visual Analysis (Power BI)

Using Power BI, the cleaned dataset was imported and a dashboard was created with:

- Pie chart of survival rate
- Bar chart of survival by gender- Histogram of age distribution
- Stacked bar of survival by class

Filters and slicers were added for interactivity, allowing users to explore data from different angles.

---

## ✅ Conclusion

This project demonstrates the full cycle of a beginner-level data analysis workflow. We successfully cleaned, explored, and visualized Titanic passenger data using Python and Power BI. The findings confirmed historical patterns such as women and upper-class passengers having better survival rates. By integrating Jupyter for scripting and Power BI for dashboarding, we gained both statistical and visual insights.

Uploading the project to GitHub with full documentation also ensures it can be reused, improved, or showcased. As a beginner, this project is an ideal foundation for building stronger data skills and transitioning into more advanced analysis or machine learning.

---

## 📚 References

- Kaggle Titanic Dataset: https://www.kaggle.com/competitions/titanic/data
- Seaborn Documentation: https://seaborn.pydata.org
- Power BI Tutorials: https://learn.microsoft.com/en-us/power-bi/
