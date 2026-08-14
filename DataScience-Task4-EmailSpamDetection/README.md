# Email Spam Detection with Machine Learning

## Oasis Infobyte Data Science Internship — Task 4

### Objective

Build a Natural Language Processing (NLP) binary classification model that distinguishes **spam messages** from legitimate **ham messages**.

The project uses text preprocessing and machine learning techniques to transform messages into numerical features and classify them as either spam or ham.

## Dataset

The project uses the **SMS Spam Collection Dataset**, a commonly used dataset for spam detection and text classification.

The dataset contains SMS messages labeled as:

* **Spam** — unwanted or fraudulent messages
* **Ham** — legitimate messages

The dataset will be explored, cleaned, and prepared before applying machine learning models.

## Project Workflow

The project follows these major steps:

1. Import Required Libraries
2. Load the Dataset
3. Understand the Dataset
4. Clean and Organize the Data
5. Check Missing Values
6. Check and Remove Duplicate Messages
7. Analyze Spam and Ham Class Distribution
8. Text Preprocessing
9. Lowercase Conversion
10. Punctuation and Unwanted Character Removal
11. Stopword Removal
12. Optional Stemming/Lemmatization
13. Understand TF-IDF
14. TF-IDF Feature Extraction
15. Prepare Features and Target
16. Train-Test Split
17. Train Multinomial Naive Bayes Model
18. Train Logistic Regression Model
19. Make Predictions
20. Evaluate Model Performance
21. Compare Classification Models
22. Analyze Confusion Matrices
23. Discuss the Importance of Recall
24. WordCloud Visualization
25. Select the Best-Performing Model
26. Final Interpretation
27. Conclusion

## Machine Learning Models

The project compares at least two classification algorithms:

* Multinomial Naive Bayes
* Logistic Regression

These models are suitable for text classification using TF-IDF features.

## Text Processing

The text preprocessing pipeline includes techniques such as:

* Lowercase conversion
* Punctuation removal
* Unwanted character removal
* Stopword removal
* Optional stemming or lemmatization

## Feature Extraction

**TF-IDF (Term Frequency-Inverse Document Frequency)** is used to convert text messages into numerical feature vectors that can be processed by machine learning algorithms.

## Evaluation Metrics

The classification models will be evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

Special attention will be given to **recall**, since incorrectly classifying a spam message as a legitimate message is an important error in spam detection.

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Matplotlib
* Seaborn
* WordCloud

## Project Structure

```text
DataScience-Task4-EmailSpamDetection/
│
├── Email_Spam_Detection_ML.ipynb
├── README.md
└── screenshots/
```

## Results

The final model performance, evaluation metrics, model comparison, and best-performing model will be added after completing the machine learning workflow.

## Conclusion

This project demonstrates an end-to-end NLP classification workflow, including text preprocessing, TF-IDF feature extraction, machine learning model training, evaluation, and comparison for spam message detection.

## Internship Details

**Organization:** Oasis Infobyte
**Program:** OIBSIP Data Science Internship
**Track:** Data Science
**Task:** Task 4 — Email Spam Detection with Machine Learning
