# Car Price Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting the selling price of used cars using Machine Learning regression techniques.

The project was completed as part of the **Oasis Infobyte Data Science Internship – Task 3: Car Price Prediction**.

The dataset contains information about used cars, including their brand, manufacturing year, kilometers driven, fuel type, seller type, transmission, ownership history, and selling price.

The project covers the complete Machine Learning workflow, from data preprocessing and exploratory data analysis to model training, evaluation, and feature importance analysis.

---

## 🎯 Objective

The main objective of this project is to develop a Machine Learning model that can predict the selling price of a used car based on its available features.

---

## 📊 Dataset

The project uses a used-car dataset containing the following major attributes:

- `name` – Name of the car
- `year` – Manufacturing year
- `selling_price` – Selling price of the car
- `km_driven` – Kilometers driven
- `fuel` – Fuel type
- `seller_type` – Type of seller
- `transmission` – Transmission type
- `owner` – Ownership history

The dataset was cleaned and transformed before model training.

After preprocessing and duplicate removal, the dataset contained **3,577 records**.

---

## 🛠️ Technologies and Libraries

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Development Environment
- Google Colab
- Jupyter Notebook

---

## 🔄 Project Workflow

The project follows these major steps:

1. Import required libraries
2. Load the dataset
3. Inspect the dataset
4. Check missing values and duplicates
5. Clean and standardize categorical values
6. Perform feature engineering
7. Analyze the dataset using Exploratory Data Analysis
8. Encode categorical variables
9. Prepare features and target
10. Analyze feature correlations
11. Split the dataset into training and testing sets
12. Preprocess the data using One-Hot Encoding
13. Train Machine Learning models
14. Generate predictions
15. Evaluate model performance
16. Compare different regression models
17. Select the best-performing model
18. Analyze feature importance
19. Interpret the final model
20. Draw project conclusions

---

## 🧹 Data Preprocessing

The dataset was checked for:

- Missing values
- Duplicate records
- Inconsistent categorical values
- Data types
- Unique categorical values

The dataset contained **763 duplicate records**, which were removed during data cleaning.

Categorical values were standardized to maintain consistency.

---

## ⚙️ Feature Engineering

Two additional features were created:

### Brand

The car manufacturer was extracted from the `name` column to create a new `brand` feature.

### Car Age

Car age was calculated from the manufacturing year:

```text
Car Age = Current Year - Manufacturing Year
