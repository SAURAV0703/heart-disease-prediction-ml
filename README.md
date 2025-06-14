# 🫀 Heart Disease Prediction using Machine Learning
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

This project predicts the likelihood of heart disease in individuals using machine learning. It follows a clean data science pipeline — from cleaning real-world medical data to exploratory data analysis (EDA), then training multiple models to identify at-risk individuals with high accuracy.

---  

## 📌 Overview

- **🎯 Goal**: Detect the presence of heart disease using machine learning.
- **📂 Dataset**: A real-world cardiovascular dataset (`cardio_train.csv`).
- **📚 Process**: Cleaning → EDA → ML Training
- **🔍 Algorithms**: Logistic Regression, SVM, Random Forest, XGBoost
- **📊 Evaluation**: Accuracy, ROC Curve, Confusion Matrix

---

## 📁 Project Structure

| File                                | Description                                                         |
|-------------------------------------|---------------------------------------------------------------------|
| `cardio_train.csv`                  | 📥 Raw dataset (unprocessed cardiovascular data)                    |
| `cleaning.ipynb`                    | 🧹 Preprocesses raw data: removes noise, handles missing/outlier values |
| `cleaned_heart_disease_data.csv`   | ✅ Output of cleaning step — used for EDA                           |
| `EDA.ipynb`                         | 📊 Visual exploration: distributions, correlation, insights         |
| `cleaned_data.csv`                 | 🔁 Final pre-processed dataset after EDA — used for model training  |
| `training.ipynb`                    | 🤖 Trains models and evaluates them                                 |

---
## 🔄 Data Flow Summary

1. 📝 **Raw Data**  
   `cardio_train.csv`

   ⬇️

2. 🧹 **Cleaning Notebook**  
   `cleaning.ipynb`  
   ➡️ Output: `cleaned_heart_disease_data.csv`

   ⬇️

3. 📊 **Exploratory Data Analysis (EDA)**  
   `EDA.ipynb`  
   ➡️ Output: `cleaned_data.csv`
   
   ⬇️

5. 🤖 **Model Training & Evaluation**  
   `training.ipynb`

---
## 🧠 Tech Stack

| Category       | Tools & Libraries                              |
|----------------|------------------------------------------------|
| **Language**   | Python                                          |
| **Data Handling** | Pandas, NumPy                              |
| **Visualization** | Matplotlib, Seaborn                        |
| **ML Libraries** | Scikit-learn, XGBoost                        |
| **Tools**      | Jupyter Notebook, Google Colab, Git, GitHub   |

---

## 🌐 Run Options

You can run the notebooks using:

- ✅ **Jupyter Notebook**
- ✅ **VS Code with Python extension**
- ✅ **Google Colab** (easiest for quick testing!)

---

## 🚀 Project Highlights

- 📊 Clean EDA pipeline
- 🔍 Model comparison (Logistic Regression, SVM, Random Forest, XGBoost)
- 📈 Evaluation via Accuracy, Confusion Matrix, and ROC AUC
- 🧹 Structured cleaning → clear data flow between files
- 🎓 Ready for college projects, resumes, or interviews

---

## 🤝 How to Use or Contribute

- 🔁 Fork this repo and experiment with your own dataset
- 🧪 Try tuning the models for better accuracy
- 🌐 Build a frontend using **Streamlit** or **Flask**
- 📄 Use it as part of academic submissions (with credits!)

---

## 📜 License

This project is licensed under the **MIT License** — feel free to use, modify, and share it. Just give credit back by linking this repo.

---

## 🙋 Author

**Saurav Singh Negi**  
🎓 B.Tech Student | 💻 Machine Learning Enthusiast  
🔗 [GitHub: SAURAV0703](https://github.com/SAURAV0703)

---
