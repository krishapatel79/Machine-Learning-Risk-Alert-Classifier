# Risk Alert Classifier

A Machine Learning classification project that predicts an individual's **Risk Alert Level** using demographic, health, and lifestyle information. The project includes complete data preprocessing, handling missing values, exploratory data analysis (EDA), feature scaling, class imbalance techniques, multiple classification models, hyperparameter tuning, and model evaluation.

---

## Project Overview

The objective of this project is to build a classification model capable of identifying whether an individual belongs to a high-risk or low-risk category based on the given dataset.

The project follows the complete Machine Learning workflow from data preprocessing to model evaluation and comparison.

---

## Dataset

**Dataset Name:** Risk_Alert_Classifier_Dataset_4600.csv

The dataset contains demographic and health-related information used for predicting risk levels.

---

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Exploration
4. Data Cleaning
5. Handle Missing Values using KNN Imputer
6. Encode Categorical Features
7. Exploratory Data Analysis (EDA)
8. Feature Scaling using StandardScaler
9. Train-Test Split
10. Handle Class Imbalance
    - Random Under Sampling
    - Random Over Sampling
    - SMOTE
    - ADASYN
11. Train Machine Learning Models
12. Hyperparameter Tuning
13. Model Evaluation
14. ROC Curve Analysis
15. Model Comparison

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn

---

## Machine Learning Algorithms

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## Class Imbalance Techniques

- Random Under Sampling
- Random Over Sampling
- SMOTE
- ADASYN

---

## Data Preprocessing

- Missing Value Handling using KNN Imputer
- Label Encoding
- Feature Scaling using StandardScaler
- Train-Test Split

---

## Hyperparameter Tuning

The project improves model performance using:

- GridSearchCV
- RandomizedSearchCV

---

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- Classification Report

---

## Project Structure

```
Risk-Alert-Classifier/
│
├── Risk_Alert_Classifier_Dataset_4600.csv
├── Risk_Alert_Classifier.ipynb
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Risk-Alert-Classifier.git
```

Go to project directory

```bash
cd Risk-Alert-Classifier
```

Install required libraries

```bash
pip install -r requirements.txt
```

---

## Required Libraries

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn
```

---

## How to Run

1. Download the dataset.
2. Open the Jupyter Notebook.
3. Run all cells sequentially.
4. Compare the performance of different classification models.

---

## Results

The project compares multiple classification algorithms after applying different class balancing techniques. Performance is evaluated using standard classification metrics, confusion matrix, and ROC-AUC score to determine the best-performing model.

---

## Future Improvements

- Deploy using Streamlit
- Add XGBoost and LightGBM models
- Perform feature selection
- Save the best trained model using Pickle
- Create a web application for prediction

---
