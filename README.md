# Employee Attrition Prediction System

## Project Overview

Employee attrition is a major challenge for organizations as it leads to increased recruitment costs, loss of experience, and reduced productivity.
This project develops a **Machine Learning model** that predicts whether an employee is likely to leave the company based on various factors such as job satisfaction, salary, work environment, and experience.

The goal is to help organizations identify employees at risk of leaving and take preventive actions to improve employee retention.

---

## Dataset

The dataset used for this project is the **IBM HR Analytics Employee Attrition Dataset**.

It includes information about employees such as:

* Age
* Department
* Job Role
* Monthly Income
* Job Satisfaction
* Years at Company
* Work-Life Balance
* Overtime
* Attrition (Target Variable)

Target Variable:

* **Attrition**

  * Yes → Employee left the company
  * No → Employee stayed in the company

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## Machine Learning Model

The project uses a **Random Forest Classifier** to predict employee attrition.

Steps involved:

1. Data Loading
2. Data Exploration
3. Data Preprocessing
4. Feature Engineering
5. Train-Test Split
6. Model Training
7. Model Evaluation

---

## Model Evaluation Metrics

The model performance is evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

These metrics help assess how well the model predicts employee attrition.

---

## Key Insights

From the analysis, several important factors affecting employee attrition were identified:

* Employees who work **overtime frequently** are more likely to leave.
* **Low job satisfaction** increases the chances of attrition.
* Employees with **lower monthly income** tend to leave more often.
* Employees with **fewer years at the company** show higher attrition rates.
* **Work-life balance** significantly impacts employee retention.

---

## Project Structure

```
Employee-Attrition-Prediction-System
│
├── employee_attrition_prediction.ipynb
├── README.md
└── dataset.csv
```

---

## Conclusion

This project demonstrates how machine learning can be used to predict employee attrition and help organizations make data-driven decisions to improve employee retention strategies.

---

## Author

Priyanka Gadekar
BTech Data Science Student

