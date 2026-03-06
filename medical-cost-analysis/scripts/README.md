# Scripts

This directory contains the source analysis files used to conduct the statistical investigation for the **Medical Cost and Lifestyle Analysis** project.

## Contents

- **Medical_Cost_Analysis.qmd**  
  The primary Quarto document used to perform the complete analysis.  
  This file contains the code, visualizations, statistical modeling, and written interpretation used to generate the final HTML report located in the `reports` directory.

## Analysis Workflow

The analysis performed in this project follows a typical data science workflow:

1. **Data Loading**
   - Import the insurance dataset into the R environment.

2. **Data Exploration**
   - Examine dataset structure and summary statistics.
   - Identify distributions and potential relationships between variables.

3. **Exploratory Data Analysis**
   - Create visualizations to understand patterns in the data.
   - Investigate how demographic and lifestyle factors relate to insurance charges.

4. **Statistical Modeling**
   - Fit linear regression models to explain variation in insurance charges.
   - Evaluate model coefficients and statistical significance.

5. **Model Refinement**
   - Compare alternative model specifications.
   - Apply feature selection techniques including LASSO regression.

6. **Interpretation**
   - Interpret model results to determine which factors most strongly influence medical insurance costs.

## Purpose

Separating the analysis scripts from the final report helps maintain a clear and reproducible workflow. The files in this directory represent the core analytical work that produces the outputs presented in the `reports` folder.

All analysis in this project was performed using **R** and rendered using **Quarto**.
