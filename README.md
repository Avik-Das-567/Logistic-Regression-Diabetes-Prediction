# Logistic Regression with Streamlit - Diabetes Prediction
### App Link: 
* https://logistic-regression-diabetes-prediction.streamlit.app/
## Example Problem
* Diabetes Prediction Based on Age and Glucose Level
* We have data about **Age**, **Glucose Level**, and **Diabetes (Yes or No)**.
## How It Works
* Load the data using **`pd.read_csv()`**
* **Map Yes/No to 1/0** for machine learning
* Train a model using **`LogisticRegression()`**
* Ask user inputs for **Age** and **Glucose**
* Show the result using **`st.write()`**
