# Cancer Prediction Project

This project uses machine learning to predict cancer diagnoses from a dataset (`Cancer.csv`). It includes data cleaning, exploratory data analysis (EDA), and classification using Logistic Regression and Support Vector Machine (SVM).

# Overview

- Data Preprocessing:  
  - Clean the dataset by dropping unnecessary columns and checking for null values.
  
- Exploratory Data Analysis:  
  - Generate descriptive statistics and a correlation heatmap to understand feature relationships.
  
- Modeling:  
  - Implement Logistic Regression with different train-test splits.
  - Use SVM with an RBF kernel for non-linear classification.
  
- Evaluation:  
  - Compare models using accuracy scores, confusion matrices, and classification reports.
  - Visualize model performance using a bar plot.

# Requirements

- Python 3.x  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

Install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
