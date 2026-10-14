# 🏥 Insurance Data Analysis & Linear Regression

## 📌 Project Overview

This project explores the **Insurance dataset** through comprehensive **Exploratory Data Analysis (EDA)** to uncover patterns, relationships, and key insights. After preprocessing the data, a **Linear Regression** model is built to predict medical insurance charges based on various demographic and health-related features.

---

## 🎯 Objectives

* Perform in-depth Exploratory Data Analysis (EDA)
* Understand feature distributions and relationships
* Identify missing values and duplicate records
* Analyze correlations between variables
* Visualize trends using informative plots
* Preprocess the dataset for Machine Learning
* Build and evaluate a Linear Regression model

---

## 📂 Dataset

The dataset contains the following features:

| Feature  | Description                                 |
| -------- | ------------------------------------------- |
| age      | Age of the insured person                   |
| sex      | Gender                                      |
| bmi      | Body Mass Index                             |
| children | Number of dependent children                |
| smoker   | Smoking status                              |
| region   | Residential region                          |
| charges  | Medical insurance charges (Target Variable) |

---

## 📊 Exploratory Data Analysis

The notebook includes:

* Dataset overview
* Summary statistics
* Missing value analysis
* Duplicate value detection
* Distribution plots
* Count plots
* Box plots
* Correlation heatmap
* Pairwise relationship analysis
* Outlier detection
* Feature relationship analysis

---

## 🤖 Machine Learning

**Model Used**

* Linear Regression

### Model Workflow

1. Data Cleaning
2. Feature Encoding
3. Train-Test Split
4. Model Training
5. Model Evaluation
6. Prediction

---

## 📈 Evaluation Metrics

The model is evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📁 Repository Structure

```text
├── insurance.ipynb    # EDA, preprocessing, visualization, and Linear Regression
├── insurance.csv      # Dataset
└── README.md
```

---

## 💡 Key Insights

* Smoking status has a significant impact on insurance charges.
* Age and BMI show a positive relationship with medical expenses.
* Data visualization helps identify trends, outliers, and feature interactions.
* Linear Regression serves as a strong baseline model for predicting insurance costs.

---

## 🚀 Future Improvements

* Implement Decision Tree and Random Forest Regression
* Compare multiple regression algorithms
* Perform hyperparameter tuning
* Apply feature engineering techniques
* Deploy the model using Streamlit or Flask

---

