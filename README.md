# Student-Placement-Predictor-ML

# 🎓 Student Placement Predictor using Machine Learning

## 📝 Overview
This project is a Machine Learning model built using Python that predicts whether a college student will get placed in campus interviews or not. It analyzes various student skills and academic details to make real-time predictions and helps understand which skills matter the most for placements.

## 🚀 Key Features
* **Multi-Model Comparison:** Trains and compares the accuracy of 3 different algorithms (Logistic Regression, Decision Tree, and Random Forest).
* **Smart Saving (Joblib):** Saves the trained model as a `.pkl` file so it loads instantly without needing to train from scratch every time.
* **Interactive CLI Predictor:** A continuous loop where users can enter real-time student data and get instant probability scores for placement.
* **Feature Importance Analysis:** Visually demonstrates which specific skill (CGPA, Aptitude, Internship, etc.) holds the highest weightage in the model's decision-making process.

## 🛠️ Tech Stack Used
* **Language:** Python
* **Data Manipulation:** Pandas
* **Machine Learning:** Scikit-Learn (RandomForestClassifier, LogisticRegression, DecisionTreeClassifier)
* **Visualization:** Matplotlib
* **Model Export:** Joblib

## 📊 Data Input Parameters
The model takes 5 key features to predict the outcome:
1. **CGPA** (Academic Score)
2. **Aptitude** (Logical & Quantitative Score)
3. **Communication** (Soft Skills Score)
4. **Projects** (Number of projects completed)
5. **Internship** (Yes/No)

## 💻 How to Run this Project
1. Clone this repository to your local machine.
2. Ensure you have the required libraries installed (`pip install pandas scikit-learn matplotlib joblib`).
3. Place the `students_data.csv` in the same directory.
4. Run the python script: `python main.py`
5. Enter the student details when prompted in the terminal to see the prediction!

---
*Built with ❤️ for Machine Learning.*
