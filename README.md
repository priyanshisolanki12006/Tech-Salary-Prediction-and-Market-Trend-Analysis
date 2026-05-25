# Tech Salary Prediction and Market Trend Analysis using Glassdoor Jobs Dataset

## Project Overview

The technology industry is one of the fastest-growing sectors, where salaries vary significantly based on job role, company size, location, industry, and company reputation. This project aims to analyze salary trends in the tech industry and build a Machine Learning model to predict salaries using job posting data from Glassdoor (2017–2018).

Using **Exploratory Data Analysis (EDA)** and **Machine Learning techniques**, this project identifies key salary-driving factors and predicts salary ranges for technology-related job roles.

---

## Problem Statement

Salary structures in the technology industry differ significantly across job roles, company sizes, industries, and locations. Understanding these salary patterns is important for:

- **Job Seekers** – To understand expected salary ranges and negotiate compensation.
- **Employers** – To design competitive salary structures.
- **Recruiters** – To benchmark salaries fairly.
- **Analysts & Researchers** – To identify compensation trends in the market.

The goal of this project is to analyze salary patterns and build a predictive model to estimate salaries based on job-related attributes.

---

## Dataset Information

**Dataset:** Glassdoor Jobs Dataset (2017–2018)

The dataset contains job postings collected from Glassdoor and includes features such as:

- Job Title
- Salary Estimate
- Company Rating
- Company Size
- Industry
- Sector
- Revenue
- Headquarters
- Location
- Type of Ownership
- Competitors
- Job Description

---

## Project Type

**EDA + Regression (Machine Learning)**

---

## Technologies Used

- **Python**
- **Google Colab**
- **Pandas** – Data manipulation
- **NumPy** – Numerical computation
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-Learn** – Machine Learning models
- **SciPy** – Statistical testing

---

## Project Workflow

### 1. Data Understanding
- Dataset loading
- Data inspection
- Missing value analysis
- Duplicate checking

### 2. Data Wrangling
- Cleaning salary columns
- Feature engineering
- Handling missing values
- Outlier treatment

### 3. Exploratory Data Analysis (EDA)
- Salary distribution analysis
- Salary by job title
- Salary by company size
- Location-wise salary comparison
- Industry-wise salary trends
- Correlation heatmap
- Pair plot analysis

### 4. Hypothesis Testing
Performed statistical testing using:
- Independent T-Test
- ANOVA Test
- Pearson Correlation Test

### 5. Feature Engineering & Preprocessing
- Missing value handling
- Outlier treatment using IQR
- Categorical encoding
- Feature selection
- Data scaling
- Train-test splitting

### 6. Machine Learning Models
The following regression models were implemented:

1. **Linear Regression**
2. **Decision Tree Regressor**
3. **Random Forest Regressor**

### 7. Hyperparameter Tuning
Used **GridSearchCV** for model optimization.

---

## Evaluation Metrics

The models were evaluated using:

- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Squared Error)**
- **R² Score**

---

## Final Model Selection

**Random Forest Regressor** was selected as the final model because it achieved:

- Better prediction accuracy
- Higher R² Score
- Lower MAE & RMSE
- Reduced overfitting

---

## Key Insights

- Salary varies significantly across **job roles**.
- **Location** strongly impacts salary levels.
- Large companies generally offer better compensation.
- Certain industries provide higher salary packages.
- Company ratings may influence salary trends.

---

## Conclusion

This project successfully analyzed salary trends in the technology industry and built a machine learning model for salary prediction. The analysis revealed that factors such as **job title, location, company size, industry, and company ratings** significantly influence salary levels.

Among all models, the **Random Forest Regressor** performed best due to its higher prediction accuracy and better generalization ability. This project can help **job seekers, recruiters, employers, and analysts** make informed compensation-related decisions.

---

## Author

**Priyanshi Solanki**
