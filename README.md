# Graduate Admissions Analysis – Jamboree Case Study

## Context

Jamboree has helped thousands of students like you make it to top colleges abroad. Be it **GMAT, GRE, or SAT**, their unique problem-solving methods ensure maximum scores with minimum effort.

They recently launched a feature where students/learners can visit their website and check their **probability of getting into an Ivy League college**. This feature estimates the chances of graduate admission from an **Indian perspective**.

---

## How Can You Help Here?

Your analysis will help Jamboree:

- Understand which factors are important in graduate admissions  
- Identify how these factors are interrelated  
- Predict a student’s **chance of admission** based on given variables  

---

## Dataset

- **Dataset Name:** `jamboree_admission.csv`

---

## Column Profiling

- **Serial No.** – Unique row identifier  
- **GRE Score** – Out of 340  
- **TOEFL Score** – Out of 120  
- **University Rating** – Out of 5  
- **SOP & LOR Strength** – Out of 5  
- **Undergraduate GPA** – Out of 10  
- **Research Experience** – Binary (0 = No, 1 = Yes)  
- **Chance of Admit** – Continuous value ranging from 0 to 1  

---

## Concepts Used

- **Exploratory Data Analysis (EDA)**  
- **Linear Regression**

---

## What Does “Good” Look Like?

### 1. Data Understanding & Preparation
- Import the dataset and examine its structure and characteristics  
- Drop the **unique row identifier** column (Serial No.) to avoid model bias  

### 2. Exploratory Data Analysis
- Perform **non-graphical analysis** (summary statistics, distributions)  
- Perform **graphical analysis** to understand:
  - Distribution of applicant profiles  
  - Spread and variability of features  

### 3. Relationship Analysis
- Analyze relationships between independent variables  
- Check **correlation** among predictors and their interaction effects  
- Understand how each factor influences graduate admission chances  

### 4. Model Building
- Apply **Linear Regression** using the **Statsmodels** library  
- Interpret coefficients and statistical significance  

### 5. Linear Regression Assumptions Testing
- **Multicollinearity:** Variance Inflation Factor (VIF)  
- **Mean of Residuals:** Should be approximately zero  
- **Linearity:** No pattern in residual plots  
- **Homoscedasticity:** Constant variance of residuals  
- **Normality of Residuals:** Residuals should follow a normal distribution  

### 6. Model Evaluation
Evaluate model performance using:
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  
- R² Score  
- Adjusted R² Score  

### 7. Insights & Recommendations
- Provide **actionable insights** for students and Jamboree  
- Recommend strategies to improve admission chances  
- Try and compare **different linear regression models**

---

## Deliverable

A well-documented analysis showcasing:
- Clear EDA insights  
- Validated regression models  
- Interpretable results  
- Practical recommendations for real-world application
