# 🚢 Exploratory Data Analysis (EDA) of Titanic Dataset

## Overview
An exploratory data analysis project on the famous **Titanic dataset** using Python.
The goal is to understand the dataset's structure, clean missing values, and uncover
patterns through visualizations.

## 🛠️ Tools & Libraries Used
- Python
- Pandas & NumPy
- Matplotlib
- Seaborn
- Google Colab

## 📁 Files
- `EDA_of_Titanic_data_set.ipynb` - Main EDA notebook

## 📊 Dataset
- **Source:** Seaborn's built-in Titanic dataset
- **Size:** 891 rows × 15 features
- **Features:** 6 quantitative, 9 qualitative (age, sex, class, survived, fare, etc.)

## 🔍 Key Steps

### 1. Data Loading & Inspection
- Loaded dataset using `sns.load_dataset("titanic")`
- Explored shape, data types, and null values using `head()`, `tail()`, `info()`

### 2. Data Cleaning
- Dropped `deck` column (too many missing values)
- Filled missing `age` values with **median**
- Filled missing `embarked` and `embark_town` with **mode**

### 3. Exploratory Analysis & Visualizations
- **Age Distribution** — histogram with KDE curve
- **Age Boxplot** — to detect outliers
- **Passenger Class Distribution** — countplot
- **Gender Distribution** — countplot
- **Survival Analysis** — countplot of survived vs not survived

## 💡 Key Findings
- Most passengers were in **3rd class**
- **Age** had missing values filled using median (~28 years)
- The dataset had significant missing values in the `deck` column (dropped)
