# Customer Churn Prediction and Segmentation Using Machine Learning

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1jEX8MtcbfzeEhqesui9pWENurjUgfCwF)

---

## Project Overview

Customer churn is one of the major challenges faced by telecommunication companies. The ability to predict customer churn enables organizations to take proactive measures to retain customers and reduce revenue loss.

This project focuses on predicting customer churn using machine learning techniques and identifying meaningful customer segments using clustering algorithms.

The project combines supervised and unsupervised learning approaches to generate valuable business insights.

---

## Problem Statement

Customer attrition directly affects business growth and profitability. The objective of this project is to identify customers likely to leave the service and classify customers into distinct groups based on their behavioral characteristics.

---

## Objectives

* Analyze customer behavior patterns.
* Predict customer churn using machine learning.
* Handle class imbalance issues.
* Improve model performance using hyperparameter tuning.
* Perform feature importance analysis.
* Segment customers using clustering techniques.
* Generate actionable business insights.

---

## Dataset

Dataset: Telco Customer Churn Dataset

Features include:

* Customer tenure
* Monthly charges
* Total charges
* Contract type
* Internet service
* Payment method
* Online security
* Technical support
* Streaming services
* Customer churn status

Target variable:

* Churn

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* OpenPyXL

### Development Environment

* Google Colab
* Jupyter Notebook

---

## Machine Learning Techniques

### Supervised Learning

* Random Forest Classifier

### Unsupervised Learning

* K-Means Clustering

### Model Optimization

* Hyperparameter Tuning
* Cross Validation

---

## Project Workflow

### 1. Data Collection

The customer dataset is imported and analyzed.

### 2. Data Preprocessing

* Missing value handling
* Data cleaning
* Feature encoding
* Feature transformation

### 3. Exploratory Data Analysis

* Distribution analysis
* Correlation analysis
* Customer behavior visualization

### 4. Churn Prediction

Random Forest Classifier is trained to predict customer churn.

### 5. Model Optimization

Hyperparameter tuning improves the model's performance.

### 6. Feature Importance

Important features affecting churn are identified.

### 7. Customer Segmentation

K-Means clustering groups customers into meaningful segments.

---

## Evaluation Metrics

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC Curve
* Cross Validation

---

## Customer Segmentation

Customers are divided into groups based on behavioral patterns:

* Loyal Customers
* High-Risk Customers
* Premium Customers
* Budget Customers

These segments help businesses develop targeted retention strategies.

---

## Repository Structure

```text
Customer-Churn-Prediction-and-Segmentation/
│
├── CBSOTProject_1.ipynb
├── Telco_customer_churn.xlsx
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/krishnapp2004/Customer-Churn-Prediction-and-Segmentation.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## Open in Google Colab

The notebook can be opened directly in Google Colab using the badge at the top of this README.

---

## Business Applications

* Customer retention analysis
* Customer behavior analysis
* Churn prediction
* Marketing optimization
* Customer segmentation
* Revenue protection

---

## Future Scope

* Deployment using Streamlit or Flask
* Real-time churn prediction
* Dashboard development
* XGBoost implementation
* Deep learning models
* Automated prediction pipelines

---

## Author

P P Krishna

Bachelor of Technology in Computer Science and Engineering

---

## License

This project is developed for academic and educational purposes.

MIT License.
