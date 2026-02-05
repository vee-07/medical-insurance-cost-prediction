# Medical Insurance Cost Prediction

## Project Overview
This project focuses on analyzing and predicting medical insurance costs based on demographic and lifestyle factors using Exploratory Data Analysis (EDA) and regression techniques.

The goal is to understand the key factors influencing insurance charges and build predictive models to estimate medical insurance costs.

---

## Dataset
The dataset contains the following attributes:
- Age
- Sex
- BMI
- Number of children
- Smoking status
- Region
- Insurance charges (target variable)

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- Jupyter Notebook

---

## Project Workflow
1. Data loading and inspection
2. Data cleaning and feature engineering
3. Exploratory Data Analysis (EDA)
4. Data visualization
5. Regression modeling
   - Linear Regression
   - Polynomial Regression
6. Model evaluation using MSE and R² score

---

## Model Performance
- Linear Regression R² Score: ~0.74
- Polynomial Regression R² Score: ~0.83
- Cross-validation R² Score: ~0.82

---

## Key Insights
- Smokers incur significantly higher insurance charges
- Higher BMI is associated with increased medical costs
- Regional differences affect insurance charges
- Family size impacts insurance expenses

---

## Folder Structure

<pre>
medical-insurance-cost-prediction/
├── README.md
│
├── data/
│   └── medical_insurance.csv
│
├── code/
│   └── medical_insurance_regression.ipynb
│
├── outputs/
│   └── medical_insurance_regression.html
│
└── reports/
    └── medical_insurance_regression.pdf
</pre>

---

## Author
Vaibhav / vee-07

---

## Note
This project is created for academic and learning purposes using a publicly available dataset.
