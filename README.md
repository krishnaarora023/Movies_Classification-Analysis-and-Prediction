# 🎬📊 Movie Classification Analysis & Prediction

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange?logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Charts-red)
![Machine Learning](https://img.shields.io/badge/ML-Logistic%20Regression-purple)

---

## 📌 Project Overview

This project focuses on **Movie Classification Analysis & Prediction** 🎥 using data science techniques.  
It includes:

- 📂 Data Loading & Cleaning  
- 🔍 Exploratory Data Analysis (EDA)  
- 📊 Data Visualization  
- 🤖 Machine Learning Model (Classification)  

The goal is to analyze movie-related data and build a model that can **predict movie categories/classes** based on features.

---

## 📁 Dataset

- Dataset used: `Movie_classification.csv`
- Contains information about movies such as:
  - 🎭 Genre
  - ⭐ Ratings
  - 💰 Revenue
  - 🎬 Other attributes used for classification

---

## ⚙️ Tech Stack

| Tool | Purpose |
|------|--------|
| 🐍 Python | Programming |
| 📊 Pandas | Data Manipulation |
| 🔢 NumPy | Numerical Operations |
| 📉 Matplotlib | Basic Visualizations |
| 🎨 Seaborn | Advanced Visualizations |
| 🤖 Scikit-learn | Machine Learning |

---

## 🚀 Project Workflow

### 1️⃣ Import Libraries
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
````

---

## 2️⃣ Load Dataset 📂
```python
data = pd.read_csv("Movie_classification.csv")
df = data.copy()
````

---

## 3️⃣ Exploratory Data Analysis 🔍

## View dataset structure:

-head()

-tail()

-info()

-describe()

-Understand:

  -Missing values ❌

-Data types 🔢

-Feature distributions 📊

---

## 4️⃣ Data Cleaning 🧹

-Handle missing values

-Remove duplicates

-Fix data types

-Feature selection

---

## 5️⃣ Data Visualization 📊

## Some key visualizations:

-📈 Distribution plots

-📊 Count plots

-🔥 Heatmaps (correlation)

-📉 Pairplots

## Example:

```python
sns.heatmap(df.corr(), annot=True)
plt.show()
````

---

## 6️⃣ Model Building 🤖

## Used Logistic Regression (Binomial) for classification

## Steps:

-Split data (Train/Test)

-Train model

-Predict results

-Evaluate performance

---

## 7️⃣ Model Evaluation 📏

## Metrics used:

-✅ Accuracy

-📉 Confusion Matrix

-📊 Classification Report

---


## 📌 Key Insights 💡

-🎯 Identified important features affecting classification

-📊 Found correlations between variables

-🤖 Built a predictive model for movie classification

-📉 Improved understanding of dataset patterns

---

## 🧠 Future Improvements

-🔄 Try advanced models (Random Forest, XGBoost)

-⚙️ Hyperparameter tuning

-📊 More feature engineering

-🚀 Deployment as a web app

---

## 📂 Project Structure

## 📁 Movie-Classification-Project

│── 📄 Movies.ipynb
│── 📄 Movie_classification.csv
│── 📄 cleaned_movie.csv
│── 📄 README.md

---

## 🙌 Author

## Krishna Arora 🚀
## 📊 Data Science Enthusiast
## Linkedin:www.linkedin.com/in/krishna-arora-14ba6631b

---

## ⭐ Show Your Support

## If you like this project:

## ⭐ Star this repository

## 🍴 Fork it

## 🧠 Learn & Build more!

## 💬 “Data is the new oil, but insights are the real fuel!” 🚀
