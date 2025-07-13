# Linear-Regression-
This project implements a custom Linear Regression model using Stochastic Gradient Descent (SGD) from scratch in Python. It is designed to predict a student's Performance Index based on various academic and lifestyle features.

# Student Performance Prediction Using Custom Linear Regression (SGD)

This project demonstrates a custom implementation of **Linear Regression** using **Stochastic Gradient Descent (SGD)** to predict students' performance index based on academic habits and lifestyle factors.

---

##  Project Objective

To develop a machine learning model **from scratch** that predicts the **Performance Index** of students using the following input features:
- Hours Studied
- Previous Scores
- Extracurricular Activities
- Sleep Hours
- Sample Question Papers Practiced

---

##  Dataset

The dataset used in this project was sourced from Google and contains the following columns:

| Feature | Description |
|--------|-------------|
| `Hours Studied` | Number of hours spent studying daily |
| `Previous Scores` | Score obtained in prior exams |
| `Extracurricular Activities` | Categorical (Yes/No) |
| `Sleep Hours` | Average sleep duration |
| `Sample Question Papers Practiced` | Number of practice papers solved |
| `Performance Index` | **Target variable** – Overall performance score |

> File: `Student_Performance.csv`

---

# Technologies Used

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Scikit-learn (for data preprocessing only)

---

##  Model Details

A custom `LinearRegression` class was implemented with the following features:

- Weight and bias initialization
- Per-sample updates using SGD
- Manual gradient calculation
- Linear prediction logic


