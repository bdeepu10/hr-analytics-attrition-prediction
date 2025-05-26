# hr-analytics-attrition-prediction
Predicting employee attrition using machine learning

# HR Analytics: Employee Attrition Prediction

This project focuses on predicting whether an employee is likely to leave the company (attrition) using machine learning techniques. It uses a real-world HR dataset and explores the key drivers of attrition.

## 📌 Project Overview

Employee attrition is a major challenge for organizations. This project uses classification models to:
- Identify patterns in employee behavior
- Predict future attrition risks
- Help HR teams take proactive action

## 📂 Dataset Details

- **Name**: `Attrition.csv`  
- **Target Variable**: `Attrition` (Yes/No)  
- **Features** include:
  - Job Role
  - Department
  - Education Level
  - Monthly Income
  - Years at Company
  - Marital Status, etc.

## 🛠️ Technologies Used

- **Python**
  - `pandas`, `numpy` – data manipulation
  - `sklearn` – ML modeling (Random Forest)
  - `matplotlib`, `seaborn` – data visualization

## 🧠 Machine Learning Workflow

1. **Data Loading**:
   - Loaded `Attrition.csv` using pandas

2. **Preprocessing**:
   - Handled missing values
   - Used `LabelEncoder` to encode categorical features
   - Encoded target variable `Attrition` (Yes = 1, No = 0)

3. **Model Building**:
   - Used `RandomForestClassifier` for prediction
   - Performed an 80/20 train-test split
   - Trained the model and generated predictions

4. **Model Evaluation**:
   - Accuracy Score
   - Classification Report
   - Confusion Matrix

5. **Feature Importance**:
   - Visualized top 10 most important features

## 📈 Output

- ✅ **Model Accuracy**: ~84–87% (based on random state and data)
- 🔍 **Top Features**: `JobLevel`, `MonthlyIncome`, `YearsAtCompany`, etc.
- 📊 Confusion matrix and feature importance visualized
