# Customer Churn Prediction using Machine Learning

## Project Overview

This project predicts customer churn using machine learning techniques. Customer churn refers to customers who stop using a company's services. The goal is to identify customers who are likely to leave so that businesses can take preventive actions.

The project includes:

- Data exploration and analysis (EDA)
- Data cleaning and preprocessing
- Feature encoding and scaling
- Data visualization
- Model training and evaluation
- Comparison of multiple machine learning algorithms
- ROC Curve and AUC analysis

## Dataset

Dataset: Customer Churn Dataset

The dataset contains customer information such as:

- Gender
- Tenure
- Monthly Charges
- Total Charges
- Contract Type
- Internet Service
- Payment Method
- Churn Status

Target Variable:

- Churn (Yes/No)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

## Project Workflow

### 1. Data Understanding

- Load dataset
- Explore data structure
- Identify data types
- Check missing values
- Generate descriptive statistics

### 2. Data Preprocessing

- Handle missing values
- Convert data types
- Remove unnecessary columns
- Encode categorical features using Label Encoding
- Scale features using StandardScaler

### 3. Exploratory Data Analysis (EDA)

Visualizations include:

- Churn Distribution
- Contract Type vs Churn
- Monthly Charges Distribution
- Tenure vs Churn
- Correlation Heatmap
- Internet Service vs Churn

### 4. Train-Test Split

- 80% Training Data
- 20% Testing Data

### 5. Machine Learning Models

#### Logistic Regression

A linear classification model used as a baseline.

#### Decision Tree Classifier

A tree-based model that learns decision rules from data.

#### Support Vector Machine (SVM)

A powerful classification algorithm that finds optimal decision boundaries.

### 6. Model Evaluation

Evaluation metrics:

- Accuracy
- Error Rate
- Confusion Matrix
- Classification Report
- ROC Curve
- AUC Score

## Results

The models were compared using:

- Accuracy Score
- Error Rate
- ROC-AUC Performance

Logistic Regression and SVM achieved the best overall performance on the customer churn dataset.

## Project Structure
