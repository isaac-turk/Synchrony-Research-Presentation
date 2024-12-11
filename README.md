# Synchrony-Research-Presentation
This repository contains all the materials and analysis related to my research and presentation for the Emerging Technology Internship Interview. The focus of this project is building a predictive model for loan approval classification using machine learning techniques, specifically logistic regression.
---
### Project Overview
Loan approval is a critical aspect of risk management in the financial industry. This project investigates how key features such as loan-to-income ratio, interest rates, and prior defaults can influence the approval decision. By leveraging logistic regression, we aim to provide an interpretable and efficient model for binary classification (approved vs. declined).
---
### Contents
- **Notebook**: The Jupyter Notebook (loan_approval.ipynb) includes data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and visualization of results.
- **Presentation**: The Synchrony Presentation.pdf file summarizes key findings, methodology, and insights from the project.
- **Data**: The dataset used in this project includes synthetic loan and applicant information. Preprocessing steps such as outlier removal and feature scaling are detailed in the notebook.
---
### Key Highlights
- **Model Selection**: Logistic regression was chosen for its interpretability and efficiency in binary classification tasks.
- **Performance Metrics**:
  - Accuracy: 89% on train and tests sets
  - AUC: 0.946
  - F-1 Scores:
    - Class 0: 93%
    - Class 1: 74%
- **Top Features**
  - Previous loan defaults
  - Loan percent income
  - Loan interest rate
  - Applicant income
  - Applicant homeownership status
- **Insights and Takeaways**:
  - Sensitivity (72.62%) highlights the model's ability to identify approved loans.
  - Specificity (93.4%) ensures the model minimizes false positives.
