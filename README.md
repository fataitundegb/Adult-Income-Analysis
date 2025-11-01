# Adult-Income-Analysis

---

## 🗂 Overview

This dataset is collected for exploring the relationship between demographic and socioeconomic factors and individual income levels.
It serves as a benchmark for data analysis, machine learning, and visualization projects that aim to understand how attributes such as age, education, occupation, gender, and working hours influence whether a person earns above or below a certain income threshold (typically $50,000 per year).

The dataset helps in examining income inequality, educational impact on earnings, labor distribution, and social-economic patterns across populations.
Beyond predictive modeling, it provides a foundation for teaching and applying real-world data-cleaning, statistical analysis, and visualization techniques using tools like Excel and Power BI.

---

## 🎯 Objectives

The major objectives of this project are:

1. To explore the demographic and socioeconomic distributions of adults in the dataset.  
2. To identify relationships between income and predictors such as age, education, occupation, and gender.  
3. To perform correlation and regression analyses to determine the strength and direction of these relationships.  
4. To evaluate how well demographic attributes predict income categories.  
5. To visualize trends and comparisons using Power BI dashboards.

---

## 📊 Column Descriptions

Below is a brief explanation of each column found in the Clean_Data sheet:

- *age* — Represents the age of each respondent (e.g., 25, 45, 60).  
- *workclass* — Employment type or sector such as Private, Self-employed, Government, etc.  
- *education* — Highest level of education attained (e.g., Bachelors, Masters, High School).  
- *education_num* — Encoded version of education levels for statistical analysis.  
- *marital_status* — Respondent’s marital condition (e.g., Married, Single, Divorced).  
- *occupation* — Type of job or profession held.  
- *relationship* — Family or household relationship status (e.g., Husband, Wife, Not-in-family).  
- *race* — Self-reported race category.  
- *sex* — Gender of respondent (Male or Female).  
- *hours_per_week* — Average number of hours worked per week.  
- *native_country* — Country of origin or residence.  
- *income* — Income class, typically <=50K or >50K per annum.  

---

## 📈 Statistical Analysis Methods Used

- *Descriptive Statistics* — Computation of mean, median, mode, standard deviation, and frequency distributions using Excel.  
- *Correlation Analysis* — Conducted via the Correlation Matrix and Chart sheet to determine associations among numeric variables.  
- *Regression Analysis* — Performed on the Regresssion Analysis sheet to quantify how predictors (age, education, hours worked) affect income.  
- *Statistical Tests* — The Statistical_Tests sheet includes hypothesis testing such as t-tests or chi-square tests where applicable.  
- *Pivot Analysis* — Used to create summary tables, group-wise aggregates, and cross-tabulations for Power BI visuals.  

---

## 📉 Results and Insights

### 1. Descriptive Summary
The dataset reflects a diverse adult population with varying education levels, occupations, and income brackets.  
Most individuals fall within the middle-age range (25–50), with males working slightly longer hours per week on average than females.

### 2. Correlation Insights
Correlation results (from the Correlation Matrix and Chart sheet) show:
- Age and education have a moderate positive relationship with income level.  
- Hours worked per week correlates positively with income.  
- Gender has minimal correlation with income, suggesting income distribution is influenced more by occupation and education.

### 3. Regression Findings
Regression results (from the Regresssion Analysis sheet) indicate that:
- *Education level* and *hours_per_week* are statistically significant predictors of income.  
- The model’s R² value suggests that a fair proportion of income variance is explained by these independent variables.  
- Variables like *age* contribute positively but less significantly after controlling for education.

### 4. Statistical Tests
Hypothesis testing validates that:
- There is a significant difference in income between higher-educated and less-educated individuals.  
- No statistically significant difference was observed between male and female income groups at the chosen significance level.

---

## 📊 Power BI Visualization

Visual dashboards were created in *Power BI*, summarizing:
- Income distribution across demographic groups  
- Gender vs. education comparison  
- Age and work hours contribution to income  
- Correlation charts and regression model plots  

---


## 🧾 Summary / Conclusion

This analysis reveals that education level and weekly working hours are key determinants of adult income levels.  
The correlation and regression outputs align with expected socioeconomic patterns—higher education and more working hours often yield higher income brackets.  
Power BI visualizations further highlight disparities across gender, marital status, and occupational categories.

Overall, the project successfully demonstrates a structured analytical workflow using *Excel for computation* and *Power BI for visualization*, offering meaningful insights into adult income determinants.

---
*Author:* Fatai Ganiyu  
*Email Address:* fataitundegb@gmail.com
*Source:* [Kaggle.com](https://www.kaggle.com)  
*Tools Used:* Microsoft Excel (for data analysis) and Power BI (for visualization)
