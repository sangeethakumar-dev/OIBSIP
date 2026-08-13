# Iris Flower Classification 🌸

## OIBSIP Data Science Internship — Task 1

This project was completed as part of the **Oasis Infobyte (OIBSIP) Data Science Internship**.

The objective of this project is to build machine learning classification models that predict the species of an Iris flower based on its physical measurements.

### Project Objective

The model classifies Iris flowers into three species:

* Setosa
* Versicolor
* Virginica

using the following measurements:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

## Dataset

The Iris dataset is loaded directly from Scikit-learn using:

```python
from sklearn.datasets import load_iris
```

The dataset originally contains 150 observations and 4 numerical features.

During data-quality analysis, one exact duplicate observation was identified and removed, resulting in 149 observations.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

## Project Workflow

The project follows a complete machine learning workflow:

1. Import Required Libraries
2. Load the Iris Dataset
3. Convert the Dataset into a Pandas DataFrame
4. Understand the Dataset
5. Exploratory Data Analysis
6. Analyze Class Distribution
7. Data Visualization
8. Feature Analysis
9. Prepare Features and Target
10. Train-Test Split
11. Logistic Regression
12. K-Nearest Neighbors
13. Random Forest
14. Predictions
15. Model Evaluation
16. Model Comparison
17. Best Model Selection
18. Conclusion

## Exploratory Data Analysis

The project includes:

* Dataset shape and structure
* Data types
* Missing-value checking
* Duplicate-value checking
* Descriptive statistics
* Feature distributions
* Class distribution
* Pairplot
* Box plots
* Correlation heatmap

## Feature Analysis

The visualizations and group-level statistics show that **petal length and petal width are the most discriminative features** for distinguishing the three Iris species.

Setosa has distinctly smaller petal measurements, while Versicolor has intermediate values and Virginica generally has the largest petal measurements.

## Machine Learning Models

Three classification models were trained:

### 1. Logistic Regression

A linear classification model used as the first baseline classifier.

### 2. K-Nearest Neighbors (KNN)

A distance-based classification algorithm. Feature scaling was applied using `MinMaxScaler`.

### 3. Random Forest

An ensemble learning algorithm based on multiple decision trees. Feature scaling was not required for this tree-based model.

## Train-Test Split

The dataset was divided into:

* 80% Training Data
* 20% Testing Data

Stratified sampling was used to maintain the class distribution between the training and testing sets.

## Model Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Classification Report
* Confusion Matrix

## Model Comparison

| Model               |  Accuracy | Precision |    Recall |  F1-Score |
| ------------------- | --------: | --------: | --------: | --------: |
| Logistic Regression |     90.0% |     90.2% |     90.0% |     89.9% |
| KNN                 | **96.7%** | **97.0%** | **96.7%** | **96.7%** |
| Random Forest       |     93.3% |     93.3% |     93.3% |     93.3% |

## Best Performing Model

**K-Nearest Neighbors (KNN)** achieved the best performance among the three evaluated models.

It achieved:

* Accuracy: **96.67%**
* Precision: **97.00%**
* Recall: **96.67%**
* F1-Score: **96.67%**

The KNN confusion matrix contained only one misclassification out of 30 test samples.

Therefore, KNN was selected as the best-performing model for this particular test split.

## Conclusion

This project demonstrates a complete machine learning classification workflow, starting from dataset loading and exploratory data analysis through feature analysis, model training, evaluation, comparison, and model selection.

The analysis showed that petal measurements are particularly useful for Iris species classification, and KNN achieved the highest performance among the evaluated models.

## Project File

The main project notebook is:

`Iris_Flower_Classification.ipynb`

## Author

**Sangeetha**
