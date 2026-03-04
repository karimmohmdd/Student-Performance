# Student-Performance
# 🎓 Student Exam Score Prediction

## 📌 Project Overview
This project builds a simple machine learning model to predict students' exam scores based solely on the number of hours they studied. The project demonstrates fundamental Data Science steps including data cleaning, exploratory data analysis (EDA), model training, and performance evaluation using **Simple Linear Regression**.

## 📊 Dataset
**Source:** [Student Performance Factors (Kaggle)](https://www.kaggle.com/)  
The dataset contains various factors affecting student performance, but for this specific analysis, we are isolating two variables:
* **Feature (X):** `Hours_Studied`
* **Target (y):** `Exam_Score`

## 🧮 Mathematical Model
The linear regression model attempts to find the best-fitting straight line through the data points. The relationship is modeled as:

$$Exam\_Score = \beta_0 + \beta_1 \times (Hours\_Studied) + \epsilon$$

Where:
* $$\beta_0$$ is the y-intercept.
* $$\beta_1$$ is the slope (weight of the study hours).
* $$\epsilon$$ is the error term.
