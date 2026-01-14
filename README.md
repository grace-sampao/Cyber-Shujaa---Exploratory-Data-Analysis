# 🎉 Cyber Shujaa - Exploratory Data Analysis

This is my updated solution to the week 3 assignment in the Cyber Shujaa program 
for the **Data and AI Specialist** track.

## 🧭 Table of contents

- [🎯 Executive Summary](#-executive-summary)
- [🛠️ Tech Stack & Tools](#️-tech-stack--tools)
- [📂 Data Overview](#-data-overview)
- [🚀 Project Workflow](#-project-workflow)
  - [1. Exploratory Data Analysis (EDA)](#1-exploratory-data-analysis-eda)
  - [2. Feature Engineering](#2-feature-engineering)
- [📈 Insights & Conclusions](#-insights--conclusions)
- [💻 How to Run This Project](#-how-to-run-this-project)
- [👩🏽‍💻 Author](#-author)

## 🎯 Executive Summary

The purpose of this assignment was to develop hands-on experience on Exploratory 
Data Analysis.

We were to practice the Exploratory Data Analysis steps:

1. Initial Data Exploration
2. Handling Missing Values and Outliers
3. Univariate Analysis
4. Bivariate Analysis
5. Multivariate Analysis
6. Target Variable Analysis

* **Key Finding:** Cabin allocation decreased by passenger class. First class had 
the highest number of cabin allocations and Third class had the lowest.

## 🛠️ Tech Stack & Tools

* **Language:** Python
* **Libraries:** Pandas, Numpy, Matplotlib, Math module
* **Environment:** Jupyter Notebook / VS Code

## 📂 Data Overview

* **Source:** [Pandas documentation](https://raw.githubusercontent.com/pandas-dev/pandas/main/doc/data/titanic.csv)
* **Size:** 891 rows, 12 features
* **Target Variable:** `Survived`

## 🚀 Project Workflow

### 1. Exploratory Data Analysis (EDA)

* Handled missing values in the `Cabin`, `Age` and `Embarked` columns.
* Converted the `Survived`, `Pclass`, `Sex` and `Emabarked` columns into categorical 
data types.
* **Key Visual:** ![Plot](./plots/Accompanied:Unaccompanied%20Survivors%20&%20Casualties%20per%20Age%20Group.png)

### 2. Feature Engineering

* Engineered the `Age Group`, `Accompanied` and `Cabin Assignment` columns, bringing 
the total number of features to 15.

## 📈 Insights & Conclusions

1. *Insight 1:* The number of casualties was more than the survivors.
2. *Insight 2:* Port S recorded the lowest fares paid while Port C recorded the 
highest.

## 💻 How to Run This Project

1. **Clone the repo:**

```bash
git clone https://github.com/grace-sampao/Cyber-Shujaa---Exploratory-Data-Analysis.git
```

## 👩🏽‍💻 Author

| Platform | Link |
| :--- | :--- |
| **Blog** | [https://grace-sampao.github.io](https://grace-sampao.github.io) |
| **LinkedIn** | [Grace Sampao](https://www.linkedin.com/in/grace-sampao) |
| **X** | [@grace_sampao](https://x.com/grace_sampao) |
| **Email** | sampaograce@gmail.com |