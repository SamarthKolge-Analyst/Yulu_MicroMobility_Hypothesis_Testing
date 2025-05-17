# Yulu Micro-Mobility Demand Analysis: Hypothesis Testing & Exploratory Data Analysis

<p align="center">
  <img src="Yulu_Company_Logo.png" alt="Yulu Company" width="550" />
</p>

---

## 🎯 Objective

To analyze and identify significant factors affecting the demand for shared electric cycles in India using statistical hypothesis testing and exploratory data analysis (EDA). This will help Yulu optimize their operations by understanding usage patterns and factors impacting rental demand.

---

## 📚 About Yulu

Yulu is India’s leading micro-mobility service provider offering shared electric cycles aimed at reducing traffic congestion and providing affordable, eco-friendly first- and last-mile connectivity in urban areas. Their vehicles are conveniently located near metro stations, bus stands, corporate offices, and residential areas.

---

## Dataset

The dataset contains historical rental data with weather, season, and usage information collected over time.

| Column Name | Description |
|-------------|-------------|
| datetime | Timestamp of record |
| season | 1: spring, 2: summer, 3: fall, 4: winter |
| holiday | 1 if day is a holiday, else 0 |
| workingday | 1 if weekday and not holiday, else 0 |
| weather | 1: Clear, 2: Misty, 3: Light snow/rain, 4: Heavy rain/snow |
| temp | Temperature in Celsius |
| atemp | Feels-like temperature in Celsius |
| humidity | Humidity percentage |
| windspeed | Wind speed |
| casual | Count of casual users |
| registered | Count of registered users |
| count | Total rental count (casual + registered) |

Dataset link: [yulu_data.csv](https://drive.google.com/file/d/1qh_DleLB_TcF76n1nN8L3Dam16EJWu5O/view?usp=drive_link)

---

## Methodology

- Data Import and Cleaning  
- Exploratory Data Analysis (EDA)  
- Univariate & Bivariate Analysis (plots & statistical summaries)  
- Hypothesis Testing:  
  - 2-sample t-test (working day effect on rental count)  
  - ANOVA (rental counts across seasons and weather)  
  - Chi-square test (dependency of weather on season)  
- Insights & Recommendations  

---

## Key Concepts Used

- Bi-Variate Analysis  
- 2-Sample t-test  
- ANOVA (Analysis of Variance)  
- Chi-square Test  

---

## Results Summary

- Insights on how working days, seasons, and weather affect rental demand  
- Statistical evidence supporting or rejecting hypotheses  
- Practical recommendations for Yulu’s business strategy  

---

## 📂 Files in this Repository

| File Type         | Description                                      |
|-------------------|------------------------------------------------|
| Jupyter Notebook  | [Yulu_Hypothesis_Testing_Analysis.ipynb](https://drive.google.com/file/d/1OqjdoN29vOPiGincc6yhj_gvFEk2wMtZ/view?usp=drive_link) - Full analysis with code, plots, and conclusions |
| PDF Report        | [Yulu_Hypothesis_Testing_Analysis.pdf](https://drive.google.com/file/d/1AAe56k_j0iZ75KvhCeNmp2TLllqNz9V6/view?usp=drive_link) - PDF version of the analysis |
| Dataset           | [yulu_data.csv](https://drive.google.com/file/d/1qh_DleLB_TcF76n1nN8L3Dam16EJWu5O/view?usp=drive_link) - Dataset used for the analysis |

---

Explore our comprehensive notebook and reports to uncover in-depth insights and actionable business recommendations. Have questions or need further clarification ? Don't hesitate to reach out !

---

*💻Compiled by Samarth*

