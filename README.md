# 📊 Linear Regression on Ecommerce Customers Dataset

A complete **Machine Learning project** where I implemented **Exploratory Data Analysis (EDA)**, built a **Linear Regression model**, evaluated performance metrics, and analyzed residuals to understand customer spending behavior.

---

## 📁 Project Overview

This project focuses on predicting **Yearly Amount Spent** by customers based on their online behavior. Using the Ecommerce Customers dataset, the workflow includes:

✔ Data loading & cleaning
✔ Exploratory Data Analysis (EDA)
✔ Feature selection
✔ Train–test split
✔ Linear Regression model training
✔ Performance evaluation
✔ Residual analysis

---

## 🧰 Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib & Seaborn** (Data Visualization)
* **Scikit-Learn** (Model Building & Evaluation)

---

## 📌 Dataset

The dataset contains customer behavior features such as:

* Avg. Session Length
* Time on App
* Time on Website
* Length of Membership
* Yearly Amount Spent (Target Variable)

---

## 🔍 Exploratory Data Analysis

Performed EDA using visualizations to understand relationships between features and the target variable:

* Jointplots (Time vs Spending)
* Pairplots
* Regression plots
* Statistical summary (`describe()`)

Key insight:
➡ **Length of Membership** showed the strongest correlation with Yearly Amount Spent.

---

## 🤖 Model Building

Used Scikit-Learn’s `LinearRegression` to train the model.

```python
from sklearn.linear_model import LinearRegression
lr = LinearRegression()
lr.fit(x_train, y_train)
predictions = lr.predict(x_test)
```

---

## 📈 Model Evaluation

Evaluated the model using:

* **MAE** (Mean Absolute Error)
* **MSE** (Mean Squared Error)
* **RMSE** (Root Mean Squared Error)

Residual distribution was plotted to verify model accuracy and error consistency.

---

## 📉 Residual Analysis

A residual plot was created using:

```python
sns.displot(residuals, bins=20, kde=True)
```

This helped check whether the model errors follow a normal distribution — an important assumption for linear regression.

---

## 🏁 Conclusion

This project built a solid understanding of:

* How Linear Regression works
* How to interpret correlations
* How to evaluate predictive ML models
* How to validate model performance using residuals

It also strengthened knowledge in **EDA**, **feature engineering**, and **model diagnostics**.

---

## 📦 Repository Structure

```
├── ML Project_1(LR_Implementation).ipynb   # Main project notebook
├── README.md                                # Project documentation
```

---

## 🚀 Future Improvements

* Add feature scaling
* Compare with other regression models
* Deploy as a simple web app
* Hyperparameter tuning

---
