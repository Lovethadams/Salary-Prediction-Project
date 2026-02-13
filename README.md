# 💼 Salary Prediction Using Linear Regression

## 📌 Project Overview
This project builds a simple Machine Learning model to predict employee salary based on:

- Years of experience  
- Test score (out of 10)  
- Interview score (out of 10)  

The model is implemented using **Linear Regression** from Scikit-learn.

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- Scikit-learn  

---

## 📊 Data Preprocessing
Before training the model, the following steps were performed:

- Missing experience values were filled with "zero"
- Experience values (written in words) were converted to numeric form
- Missing test scores were replaced using the mean value

---

## 🤖 Model Training
The Linear Regression model was trained using:

**Features (X):**
- Experience  
- Test Score  
- Interview Score  

**Target (y):**
- Salary  

The trained model is then used to predict salaries for new candidates.

---
