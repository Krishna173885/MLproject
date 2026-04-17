# 🎓 Student Performance Indicator (End-to-End ML Project)

## 🚀 Overview
This is an **End-to-End Machine Learning Project** that predicts a student's **Maths Score** based on various academic and demographic factors.

The project covers the complete ML lifecycle:
- Data Collection
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Model Training
- Model Evaluation
- Deployment using Flask

---

## 🧠 Problem Statement
To predict the **math score of a student** based on:
- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Reading Score
- Writing Score

---

## 📊 Project Pipeline

1. Data Ingestion
2. Data Transformation
3. Model Training
4. Model Evaluation
5. Prediction Pipeline
6. Web App Deployment (Flask)

---

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn
- **Visualization:** Matplotlib, Seaborn
- **Web Framework:** Flask
- **Frontend:** HTML, CSS

---

## 📁 Project Structure

ML Project/
│
├── src/
│ ├── components/
│ │ ├── data_ingestion.py
│ │ ├── data_transformation.py
│ │ ├── model_trainer.py
│ │
│ ├── pipeline/
│ │ ├── predict_pipeline.py
│ │ └── train_pipeline.py
│ │
│ ├── exception.py
│ ├── logger.py
│ └── utils.py
│
├── notebooks/
│ ├── EDA STUDENT PERFORMANCE.ipynb
│ └── MODEL TRAINING.ipynb
│
├── templates/
│ ├── index.html
│ └── home.html
│
├── artifacts/
│ ├── model.pkl
│ └── preprocessor.pkl
│
├── app.py
├── requirements.txt
└── README.md
