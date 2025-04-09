# 🧠 Mental Health Data Analysis

## 📌 Project Overview

This project focuses on analyzing mental health data to uncover key factors influencing stress levels and treatment-seeking behavior across different demographics and occupations. By leveraging big data techniques and machine learning models, the aim is to generate actionable insights for mental health professionals and policymakers.

- **Course**: ALY6110 - Big Data and Data Management
- **Institution**: Northeastern University
- **Instructor**: Dr. Hema Seshadri
- **Team Members**: Neha Save, Akshay Prabhu, Jiahui Zhou, Bhavesh Sathavalli

---

## 📊 Dataset

- **Source**: [Mental Health Dataset - Kaggle](https://www.kaggle.com/datasets/bhavikjikadara/mental-health-dataset)
- **Description**: Contains survey responses regarding mental health status, treatment-seeking behavior, demographic information, lifestyle habits, and more.

---

## ⚙️ Methodology

### 🧹 Data Preprocessing
- Dropped null values (e.g., in `self_employed`)
- Removed duplicate entries
- Encoded categorical variables
- Split data into training and testing sets

### 🔍 Exploratory Data Analysis (EDA)
- Gender and occupation distributions
- Treatment-seeking trends by occupation
- Stress vs. time spent indoors
- Relationship between mental health history and family background
- Created interactive Tableau dashboards

---

## 🧠 Business Problem

The primary goal is to:
1. Understand stress contributors and treatment patterns.
2. Predict mood swings and stress levels using ML models.
3. Enable early intervention and targeted support.

---

## 🤖 Machine Learning Models

### 🎯 Target 1: Mood Swings
- **Models Used**:  
  - Decision Tree Classifier  
  - Random Forest Classifier  
  - XGBoost Classifier  
  - LightGBM Classifier  
- **Best Accuracy**: LightGBM - **98%**

### 🎯 Target 2: Growing Stress
- **Models Used**:  
  - Decision Tree Classifier  
  - Random Forest Classifier  
  - XGBoost Classifier  
  - LightGBM Classifier  
- **Best Accuracy**: Decision Tree - **99%**

---

## 💡 Key Insights

- Corporate employees and students seek treatment more frequently.
- Males are less likely to participate in mental health interviews.
- More time spent indoors correlates with higher stress levels.
- Features like `days_indoors`, `occupation`, `changes_habits`, and `mood_swings` are crucial predictors.

---

## ✅ Recommendations

- Promote mental health awareness in workplaces and academic institutions.
- Encourage outdoor activities to reduce stress.
- Use predictive models for early mental health intervention.
- Create gender-sensitive mental health programs.
- Enhance accessibility to mental health resources.
