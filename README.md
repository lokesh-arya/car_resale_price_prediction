# Car Resale Value Prediction

## Overview

This project aims to predict the resale value of used cars based on various features like age, mileage, brand, fuel type, and more. Multiple regression models are implemented and compared to determine the most accurate and reliable approach.

---

## Problem Statement

The goal is to build a machine learning model that can estimate the resale price of a car, helping both sellers and buyers make informed pricing decisions. The project involves:

* Data cleaning and preprocessing
* Exploratory data analysis (EDA)
* Model training and evaluation
* Comparison of multiple regression algorithms

---

## Dataset

* **Features include:**

  * Year of Manufacture
  * Kilometers_Driven
  * Fuel_Type
  * Transmission
  * Owner_Type
  * Mileage
  * Engine
  * Power
  * Seats

* **Target Variable:** Price
              
---

## Technologies Used

* Python
* pandas, NumPy
* matplotlib, seaborn (for visualization)
* scikit-learn

---

## Models Used

The following models were trained and evaluated:

* Simple Linear Regression
* Multiple Linear Regression
* Polynomial Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Support Vector Regressor

---

## 🔍 Results Summary

| Model             | R² Score |
| ----------------- | -------- |
| Simple Linear     | 0.62     |
| Multiple Linear   | 0.72     |
| Polynomial Linear | 0.66     |
| Decision Tree     | 0.79     |
| Random Forest     | 0.91     |
| Support Vector    | 0.86     |

✅ *Random Forest provided the best performance in terms of accuracy and generalization.*

---
