# Robust Statistical Modeling for Contaminated Data

## Project Description:
A robust regression analysis was conducted on the US Cancer dataset. It was shown that traditional statistical methods like OLS are extremely sensitive to outliers, which can lead to severe estimation bias. Advanced robust statistics was employed to mitigate effects of cellwise and rowwise outliers, providing more reliable results.

## Methodology & Results:
* **Exploratory Data Analysis:** identified skewness in socio-economic and health variables, used the Yeo Johnson transformation to normalize distribution without artificially shifting the data structure
* **Outlier Detection:** used DDC algorithm to identify cellwise anomalies then demostrated that rowwise outlier removal would result in a massive data loss
* **Regression Modeling:** studied multicollinearity with VIF and backward elimination. Then compared three regression models:
  * Classic OLS
  * MM-estimator (on DDC imputed data)
  * cellLTS
* **Results:** The robust MM-estimator significantly outperformed classic OLS

## Tools:
* **Language:** R
* **Libraries:** `robustHD`, `robustbase`, `cellWise`, `corrplot`, `car`, `MASS`
* **Core competencies:** Robust Statistics, Cellwise Outlier Detection (DDC), MM-Estimator, cellLTS, Data Imputation, Multicollinearity Mitigation

## Repository Contents:
* `Robust Regression Cancer Mortality Paper and Analysis.pdf`: 
* `Robust Regression Cancer Mortality.Rmd`: 
* `Robust Regression Cancer Mortality.pdf`: 
