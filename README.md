# ElevateLabsTask--5--Exploratory-Data-Analysis-EDA-
Extract insights using visual and statistical exploration.
# 🧠 Task 5: Exploratory Data Analysis (EDA) – Titanic Dataset

This project is part of my 30-day Data Analyst Internship, focused on performing Exploratory Data Analysis (EDA) using the Titanic dataset.

## 🔍 Objective

To analyze the Titanic dataset to extract insights, detect patterns, and visualize distributions and relationships among the features using Python libraries such as Pandas, Matplotlib, and Seaborn.

## 🧰 Tools Used

- Python
- Jupyter Notebook (via Anaconda Navigator)
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 📁 Dataset

Dataset used: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)  
Main file: `train.csv`

## ✅ EDA Steps Performed

### 1. Data Overview
- Checked data structure using `.info()` and `.describe()`
- Identified missing values

### 2. Univariate Analysis
- Visualized individual features like `Sex`, `Pclass`, `Age`, `Fare`, `Survived`
- Used histograms and bar plots

### 3. Bivariate / Multivariate Analysis
- Analyzed relationships between `Survived` and other features
- Used countplots, boxplots, heatmaps, and pairplots

### 4. Missing Values and Outliers
- Detected missing values using heatmaps
- Visualized outliers in `Fare` and `Age` using boxplots

### 5. Advanced Insights
- Created new features: `AgeGroup`, `FamilySize`, `HasCabin`
- Explored their effect on survival

## 📊 Key Observations

- Females had a much higher survival rate than males
- 1st class passengers had the highest survival rate
- Children and passengers in small families had better survival rates
- Passengers with cabin info and higher fares were more likely to survive
- Missing values were found in `Age`, `Cabin`, and `Embarked`

## 📄 Deliverables

- Jupyter Notebook (`Task5_ExploratoryDataAnalysis.ipynb`)
- PDF Report (`Task5_ExploratoryDataAnalysisReport.pdf`)

## 🔗 Submission

This task was submitted as part of my internship. GitHub repo includes:
- EDA notebook
- PDF report
- README documentation

---
