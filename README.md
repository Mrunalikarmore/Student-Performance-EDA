
# 📊 Student Performance Data Analysis

## 📌 Project Overview

This project focuses on analyzing student performance data using Python. The goal is to understand factors affecting students' academic performance.

---

## 🎯 Objectives

* Analyze student scores
* Identify patterns and trends
* Understand impact of different features on performance

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn

---

## 📂 Dataset

The dataset contains information about student marks, study time, and other factors affecting performance.

---

## 📈 Key Analysis

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Visualization of student performance
* Correlation analysis

---

**key finding of the data **

after analysis , we get to know that there 1000 rows and 8 columns there are no null values in the data by applying univariate and bivariate analysis we get that ,

female students have performed good on reading and writitng score while the male students have slightly lead in math score from which we get to know male are good with mathsthan females .

parental education : higherParental education have better student performance.

Test Prep:students who have** completed** the course score significantly higher in all subjects

score correlation: there's high positive correlation amoung all thre subjects -- high math scores go ususally go with high reading and writing scores.

student who have standard lunch perform better than those with **free/reduced lunch **

rece/ethencity : group E has thre highest avg math score indicationg stonger performance in math compared to others , it has 70 % of standard lunch **which is the hihgest from all the groups. this shows that the **group E students mostly cone from more economically stable backgrounds as highest higest standard lunch shoes that there is no need for financial lunch add.

**In this project, the following steps were performed:**

Filtering & Selection: Focused on specific columns like gender, race/ethnicity, parental education, lunch type, and test scores.

**Exploratory Data Analysis (EDA):
**
1.Visualized score distributions across genders, race groups, and lunch types.

2.Plotted histograms and boxplots to find patterns in student performance.

3.Used groupby and crosstab to explore relationships between categories.

Feature Engineering:
Created new features such as average score or passed/failed based on test scores.

Encoded categorical variables like lunch,gender,test preparation course for future ML use.

Contingency Table Analysis:
1.used crosstabs to analyze distribution of lunch types across racial groups.

---

## 🚀 How to Run

1. Open the notebook file
2. Install required libraries:

   ```
   pip install pandas numpy matplotlib seaborn
   ```
3. Run all cells

---

## 📌 Conclusion

This project helps in understanding how different factors influence student performance using data analysis techniques.
