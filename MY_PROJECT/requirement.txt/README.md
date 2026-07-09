SIMPLE LINEAR_REGRESSION : SALARY PREDICTION

A beginner-friendly Machine Learning project that predicts an employee's salary based on years of experience using Simple Linear Regression. This project demonstrates the complete machine learning workflow, from data preprocessing to model evaluation and model serialization.

---

Project Overview

This project uses a Simple Linear Regression model from Scikit-learn to analyze the relationship between Years of Experience and Salary.

The workflow includes:

- Data loading
- Exploratory Data Analysis (EDA)
- Data visualization
- Train-Test Split
- Model training
- Model evaluation
- Saving the trained model
- Saving the regression plot

---

Project Structure

```
MY_PROJECT/
│
├── Data/
│   └── Salary_dataset.csv
│
├── notebooks/
│   └── notebook.ipynb
│
├── model/
│   └── linear_model.pkl
│
├── images/
│   └── regression_plot.png
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

---

Dataset

The dataset contains two columns:

| Feature | Description |
|----------|-------------|
| YearsExperience | Employee's years of experience |
| Salary | Employee's salary |

---

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook

---

Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Explore Dataset
4. Data Visualization
5. Feature Selection
6. Train-Test Split
7. Train Simple Linear Regression Model
8. Make Predictions
9. Evaluate Model
10. Save Model using Joblib
11. Save Regression Plot

---

 Model Performance

| Metric | Value |
|---------|---------|
| RMSE | 7059.04 |
| R² Score | 0.9024 |

> The model explains approximately 90% of the variance in salary based on years of experience.

---

📌 Key Learnings

- Understanding Simple Linear Regression
- Data Visualization using Matplotlib
- Splitting data into training and testing sets
- Training a Machine Learning model
- Evaluating model performance using RMSE and R² Score
- Saving trained models with Joblib


Author

Guneet Kaur
