# student-performance-analysis
The goal of this project is to analyze student performance data and understand the factors affecting final grades (G3). Additionally, a machine learning model is built to predict final grades using early academic indicators.

# Student Performance Analysis 📊

## 📌 Problem Statement
The goal of this project is to analyze student performance data and understand the factors affecting final grades (G3), with a focus on academic, social, and lifestyle attributes.

## 📂 Dataset
- Student Performance Dataset
- Features include:
  - Academic grades (G1, G2)
  - Family background (Medu, Fedu)
  - Alcohol consumption (Dalc, Walc)
  - Study time, absences, and more

## 🔍 Exploratory Data Analysis (EDA)
- Analyzed correlation between features and final grade (G3)
- Visualized:
  - Medu vs G3
  - Dalc / Walc vs G3
  - Actual vs Predicted G3

## 🤖 Model Used
- **Linear Regression**
- Target variable: `G3`
- Evaluation Metric: **Mean Absolute Error (MAE ≈ 1.26)**

## 📈 Results
- Strong correlation observed between G1, G2 and G3
- Alcohol consumption showed weak correlation with final grades
- Model predictions closely match actual grades

## 🛠 Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab

## 📌 Conclusion
This project demonstrates how exploratory data analysis and simple machine learning models can provide meaningful insights into student academic performance.

⭐ Feel free to explore the notebook and visuals!

