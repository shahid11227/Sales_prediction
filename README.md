![Sales Prediction](SALES%20PREDICTION.jpeg)
# Sales_prediction

Sales Prediction Using Simple Linear Regression
 Project Overview

This project focuses on predicting product Sales based on advertising expenditure using Simple Linear Regression in Python. The objective is to analyze the relationship between TV advertising budget and Sales and build a predictive model to support data-driven marketing decisions.

 Objective

Analyze advertising data

Build a Simple Linear Regression model

Evaluate model performance

Generate business insights from predictions

 Dataset Description

The dataset contains advertising expenditures across different platforms:

TV – TV advertising budget

Radio – Radio advertising budget

Newspaper – Newspaper advertising budget

Sales – Product sales (target variable)

For this project, we use TV advertising as the independent variable to perform Simple Linear Regression.

🧠 Methodology
1️⃣ Data Preprocessing

Loaded dataset using Pandas

Checked for missing values

Performed basic exploratory analysis

2️⃣ Model Building

We applied Simple Linear Regression using scikit-learn.

Regression Equation:

𝑆
𝑎
𝑙
𝑒
𝑠
=
𝑐
+
𝑚
×
𝑇
𝑉
Sales=c+m×TV

Where:

c = Intercept

m = Coefficient for TV advertising

3️⃣ Train-Test Split

80% training data

20% testing data

4️⃣ Model Training
model = LinearRegression()
model.fit(X_train, y_train)
5️⃣ Model Evaluation

Mean Squared Error (MSE): 6.10

R² Score: 0.80

 Results

The model explains approximately 80% of the variance in Sales.

The average prediction error is around 2–3 sales units.

TV advertising shows a strong positive relationship with Sales.

 Business Insights

Increasing TV advertising expenditure leads to increased Sales.

The model supports data-driven marketing decisions.

Businesses can estimate expected Sales before allocating advertising budgets.

Predictive modeling helps improve marketing ROI.

 Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn

🚀 Future Improvements

Incorporate Radio and Newspaper features (Multiple Linear Regression)

Apply advanced regression techniques

Deploy as a web-based prediction app

📌 Conclusion

This project demonstrates how machine learning can be used to forecast Sales based on advertising expenditure. The model provides valuable insights that help businesses optimize marketing strategies and make informed investment decisions.
