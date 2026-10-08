## Machine Learning Internship Project

**Internship:** CodeOrbit Tech  
**Role:** Machine Learning Intern  
**Project:** 3 — Regression Model for Prediction  
**Submitted by:** Tabassum Gulnar

---

## 📌 Project Overview

This project focuses on predicting house prices using a Linear Regression machine learning model.

The California Housing dataset was used to train and evaluate the regression model. The project demonstrates the complete workflow of a basic regression problem, including data loading, preprocessing, train-test splitting, model training, prediction, and evaluation.

---

## 🎯 Objective

The main objectives of this project are:

- Select a dataset suitable for regression.
- Build a Linear Regression model.
- Predict house values using the trained model.
- Compare actual and predicted values.
- Evaluate the model using standard regression metrics.
- Visualize the predictions against actual values.

---

## 📊 Dataset

The **California Housing dataset** from Scikit-learn was used for this project.

The dataset contains **20,640 records** and **8 input features**.

The target variable is:

`MedHouseVal`

which represents the median house value.

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Loaded the California Housing dataset.
- Checked dataset information.
- Checked for missing values.
- Checked for duplicate records.
- Separated the features from the target variable.
- Split the dataset into training and testing sets.

### Train-Test Split

- Training Records: **16,512**
- Testing Records: **4,128**
- Test Size: **20%**

---

## 🤖 Machine Learning Model

A **Linear Regression** model from Scikit-learn was used.

The model was trained using the training dataset and then used to predict house values for the testing dataset.

---

## 📈 Model Evaluation

The model was evaluated using the following metrics:

| Metric | Score |
|---|---:|
| MAE | 0.5332 |
| MSE | 0.5559 |
| RMSE | 0.7456 |
| R² Score | 0.5758 |

### Interpretation

The model achieved an **R² score of 0.5758**, meaning that the model explains approximately **57.58% of the variation** in the target variable.

The results provide a reasonable baseline for a basic Linear Regression model.

---

## 📊 Visualization

An **Actual vs Predicted House Values** scatter plot was created to visualize the model's predictions.

The plot helps compare the predicted values with the actual house values from the test dataset.

---

## 🔍 Key Insights

- Linear Regression can be used as a simple baseline model for house price prediction.
- The model achieved an R² score of 0.5758.
- The predictions show a moderate relationship with the actual house values.
- More advanced models may improve prediction performance.

---

## 📝 Conclusion

This project successfully demonstrates a basic regression workflow using Linear Regression.

The model was trained on the California Housing dataset and evaluated using MAE, MSE, RMSE, and R² Score. The results show that Linear Regression provides a useful starting point for house price prediction.

---

## 🚀 Future Scope

The model can be improved by:

- Trying advanced regression algorithms such as Random Forest and Gradient Boosting.
- Performing feature scaling and feature engineering.
- Hyperparameter tuning.
- Comparing multiple regression models.
- Using additional relevant features.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Jupyter Notebook

---

## 📁 Project Files

- `House_Price_Prediction_using_Linear_Regression.ipynb` — Project notebook
- `House_Price_Prediction_Linear_Regression_Report.pdf` — Project report

---

## 👩‍💻 Author

**Tabassum Gulnar**

Machine Learning Intern — CodeOrbit Tech
