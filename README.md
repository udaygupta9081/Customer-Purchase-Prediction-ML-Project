# Machine Learning Classification Models Comparison

## Project Overview

This project focuses on solving a binary classification problem using multiple machine learning algorithms and comparing their performance.

The following models were implemented and evaluated:

- Logistic Regression
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

The project includes:

- Data preprocessing
- Pipeline creation
- Model training
- Classification reports
- Confusion matrices
- ROC-AUC evaluation
- ROC curve comparison
- Automated EDA using YData Profiling

---

## Dataset

The dataset contains customer information and a target variable indicating whether a customer made a purchase.

### Features

Examples:

- Gender
- Age
- Estimated Salary

### Target

- Purchased (0 = No, 1 = Yes)

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- YData Profiling

---

## Project Workflow

### 1. Data Preprocessing

- Data Cleaning
- Train-Test Split
- Feature Scaling
- Pipeline Construction

### 2. Model Training

Models trained:

1. Logistic Regression
2. Decision Tree Classifier
3. K-Nearest Neighbors
4. Gaussian Naive Bayes

### 3. Model Evaluation

Metrics used:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

### 4. Visualization

- Confusion Matrix
- ROC Curve
- ROC-AUC Comparison

### 5. Exploratory Data Analysis

Generated a complete profiling report using YData Profiling:

- Missing Values Analysis
- Correlation Analysis
- Statistical Summary
- Feature Distributions
- Duplicate Detection

---

## Results

| Model | Accuracy | ROC-AUC |
|---------|----------|----------|
| Logistic Regression | 0.75 | 0.636 |
| Decision Tree | 0.69 | 0.695 |
| KNN | 0.66 | 0.748 |
| Gaussian Naive Bayes | 0.75 | 0.686 |

### Best Accuracy

- Logistic Regression
- Gaussian Naive Bayes

### Best ROC-AUC

- K-Nearest Neighbors (0.748)

---

## ROC Curve

The ROC curve was used to compare the classification performance of all models across different thresholds.

---

## How to Run

### Clone Repository

```bash
git clone <repository-link>
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Notebook

Open the Jupyter Notebook and execute all cells.

---

## Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Feature Engineering
- Ensemble Methods
- Model Deployment using Streamlit

---

## Author

Uday Gupta

Aspiring Data Scientist | Machine Learning Enthusiast
