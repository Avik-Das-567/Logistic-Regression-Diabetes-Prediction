# Logistic Regression with Streamlit - Diabetes Prediction
### App Link: 
- https://logistic-regression-diabetes-prediction.streamlit.app/
---
### What is Logistic Regression?
- Logistic Regression is a **machine learning method** used to **predict Yes or No** answers.
- It helps to **classify** if something **belongs to a group or not**.
- Example: Predicting whether a person has diabetes or not.
---
### Required Python Packages
- **`scikit-learn`** - To build machine learning models
- **`streamlit`** - To build data apps
- **`pandas`** - To work with the dataset
---
### Example Problem
- **Diabetes Prediction** Based on **Age** and **Glucose Level**
- We have data about **Age**, **Glucose Level**, and **Diabetes** (**Yes** or **No**).

| Age | Glucose\_Level | Diabetes |
| --- | -------------- | -------- |
| 25  | 85             | No       |
| 30  | 90             | No       |
| 45  | 130            | Yes      |
| 50  | 150            | Yes      |
| 35  | 120            | No       |

---
### How It Works
- **Load the data** using **`pd.read_csv()`**.
- **Map Yes/No to 1/0** for machine learning.
- **Train a model** using **`LogisticRegression()`**.
- Ask for **user inputs** for **Age** and **Glucose**.
- **Show the result** using **`st.write()`**.
- Logistic Regression gives **Yes/No** or **True/False** results.
---
