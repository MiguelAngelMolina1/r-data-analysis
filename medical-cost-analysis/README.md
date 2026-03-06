# Medical Cost and Lifestyle Analysis

Author: Miguel Molina  

This project explores the relationship between personal lifestyle factors and medical insurance costs using the Medical Cost Personal Dataset. The goal of the analysis is to understand which demographic and behavioral characteristics contribute most strongly to variations in healthcare expenses.

The project combines exploratory data analysis, statistical modeling, and visualization techniques in R to identify key drivers of insurance charges and to build predictive regression models.

---

## Dataset

The dataset used in this analysis is publicly available on Kaggle:

https://www.kaggle.com/datasets/mirichoi0218/insurance

It contains information for **1,338 individuals** and includes demographic and lifestyle variables commonly used in insurance pricing models.

### Variables in the Dataset

- **age** – age of the primary beneficiary
- **sex** – gender of the insurance contractor
- **bmi** – body mass index
- **children** – number of dependents covered
- **smoker** – smoking status
- **region** – geographic region in the United States
- **charges** – individual medical insurance cost billed by health insurance

---

## Project Objectives

The primary goals of this analysis are:

- Identify which variables most strongly influence medical insurance costs
- Investigate how smoking status affects insurance charges
- Examine relationships between demographic variables and healthcare expenses
- Build and evaluate a regression model capable of predicting insurance charges

---

## Repository Structure

medical-cost-analysis
├── README.md
├── .gitignore
├── data
│   └── README.md
├── scripts
│   └── README.md
└── reports
    └── README.md

---

## Methods Used

This project uses statistical and data analysis techniques including:

- Exploratory Data Analysis (EDA)
- Data visualization
- Linear regression modeling
- Statistical interpretation of model coefficients
- Residual diagnostics and model evaluation

All analysis was conducted using **R**.

---

## Results

The analysis identifies several important predictors of insurance costs. Lifestyle variables such as smoking status and BMI show strong associations with medical expenses, while demographic factors such as age also contribute to variation in healthcare charges.

The final regression model provides insight into how these variables interact and influence insurance pricing.

---

## Report

The full analysis and visualizations can be found in the **reports** directory.
