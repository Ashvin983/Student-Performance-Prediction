# 🎓 Student Performance Prediction using Machine Learning

## 📌 Project Overview

This project predicts students' exam scores using Machine Learning algorithms. The model analyzes different factors such as study hours, attendance, parental involvement, motivation level, and access to resources to estimate the student's final exam score.


## 🎯 Problem Statement

Educational institutions want to identify the factors that influence student performance. The objective of this project is to build a machine learning model that can accurately predict student exam scores based on various academic and personal factors.


## 📂 Dataset

**Dataset Name:** Student Performance Factors

**Source:** Kaggle

The dataset contains information about students including:

- Hours Studied
- Attendance
- Parental Involvement
- Access to Resources
- Motivation Level
- Internet Access
- Family Income
- School Type
- Teacher Quality
- Gender
- Exam Score (Target Variable)


## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- GitHub


## 🔍 Methodology

### 1. Data Collection

Downloaded the Student Performance Factors dataset from Kaggle.

### 2. Data Preprocessing

- Loaded dataset
- Checked missing values
- Removed duplicate records
- Encoded categorical variables
- Scaled numerical features

### 3. Exploratory Data Analysis (EDA)

Created visualizations including:

- Exam Score Distribution
- Gender Distribution
- Attendance vs Exam Score
- Correlation Heatmap
- Model Comparison Graph

### 4. Machine Learning Models

The following regression models were trained and tested:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

### 5. Model Evaluation

Models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score


## 📊 Results

Among all the models, the Random Forest Regressor achieved the best performance with the highest R² Score and the lowest prediction error.

## 🚀 Future Scope

- Use larger educational datasets.
- Develop a web application for students and teachers.
- Improve prediction accuracy using advanced algorithms like XGBoost.
- Deploy the model using Flask or Streamlit.


## ✅ Conclusion

This project demonstrates how Machine Learning can be used to predict student performance effectively. By comparing multiple regression models, the Random Forest Regressor provided the best prediction accuracy and can be used for educational performance analysis.


## 👨‍💻 Author

**Name:** Ashvin

**Course:** B.Tech CSE(Artificial Intelligence & Machine Learning)
