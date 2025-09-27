# Heart Disease Dataset - Exploratory Data Analysis (EDA)

# EDA-Data_Cleaning

* Data loading & inspection (`pandas`, `info`, `describe`)
* Data cleaning (handling `0` values in Cholesterol & RestingBP)
* Exploratory Data Analysis (histograms, countplots, boxplots, violin plots, correlation heatmap)
* One Hot Encoding (categorical variables)
* Standardization with `StandardScaler`

## 📌 Project Overview

This project explores the **Heart Disease dataset** using Python.
The goal is to understand the data, clean missing/inconsistent values, and prepare it for further machine learning tasks.

## 🔧 Tools & Libraries

* **Python** 🐍
* **Pandas & NumPy** → Data manipulation
* **Matplotlib & Seaborn** → Data visualization
* **Scikit-learn** → Preprocessing (One Hot Encoding, StandardScaler)

## 📊 Workflow

### 1. Data Loading & Inspection

* Loaded the dataset (`heart.csv`)
* Checked shape, data types, duplicates, and descriptive statistics

### 2. Data Cleaning

* Replaced zero values in `Cholesterol` and `RestingBP` with their mean
* Rounded values for consistency

### 3. Exploratory Data Analysis (EDA)

* **Distribution Plots**: Age, RestingBP, MaxHR, Cholesterol
* **Countplots**: Heart disease cases by Sex, Chest Pain Type, Fasting Blood Sugar
* **Boxplots & Violin plots**: Relationship between Age/Cholesterol and Heart Disease
* **Correlation Heatmap**: Checked feature relationships

### 4. Data Preprocessing

* Applied **One Hot Encoding** for categorical variables
* Scaled numerical columns (`Age`, `RestingBP`, `Cholesterol`, `MaxHR`, `Oldpeak`) using **StandardScaler**

## 📂 Project Structure

```
heart_eda.ipynb   # Jupyter Notebook with full analysis
heart.csv         # Dataset 
README.md         # Project documentation
```

## 🚀 How to Run

1. Clone this repository
2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the notebook:

   ```bash
   jupyter notebook heart_eda.ipynb
   ```

## 📌 Next Steps

* Apply ML models (Logistic Regression, Random Forest, etc.)
* Perform feature selection
* Build a predictive model for heart disease
