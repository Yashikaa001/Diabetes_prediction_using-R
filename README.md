# 📊 Diabetes Prediction using R

## 🚀 Project Overview
This project implements an end-to-end machine learning pipeline in R to predict whether a patient has diabetes based on clinical health data.

Using the Pima Indian Diabetes Dataset, the model applies Logistic Regression to classify patients as diabetic or non-diabetic, achieving an accuracy of ~77.8%.

## 📂 Dataset Information
- Dataset: Pima Indian Diabetes Dataset  
- Total Records: 768 patients  
- Features: 8 input variables  
- Target: Outcome (0 = Non-Diabetic, 1 = Diabetic)

## ⚙️ Project Workflow

### 1. Data Loading
- Imported dataset using read.csv()
- Verified structure using head(), str(), summary()

### 2. Data Preprocessing
- Checked missing values
- Applied Z-score normalization
- Split data into 70% training and 30% testing

### 3. Exploratory Data Analysis (EDA)
- Correlation heatmap
- Outcome distribution
- BMI analysis
- Visualization using ggplot2

### 4. Model Building
- Logistic Regression using glm()

### 5. Model Evaluation
- Accuracy: 77.8%
- Precision: 72.4%
- Recall: 58.0%
- F1 Score: 64.4%
- Specificity: 94%

### 6. Prediction System
- Custom function for real-time prediction

## 🛠️ Technologies Used
- R
- ggplot2
- caret
- e1071
- caTools

## ▶️ How to Run
Install packages:
install.packages(c("readr","ggplot2","caret","e1071","caTools"))

Run scripts step-by-step.

## 🔮 Future Improvements
- Improve recall
- Use SMOTE
- Try Random Forest / XGBoost
- Deploy using Shiny

## 📌 Conclusion
This project demonstrates a complete data science workflow from data preprocessing to prediction.

## 🙌 Author
Your Name
