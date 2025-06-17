# Student Exam Score Prediction

This project focuses on predicting student exam performance using behavioral, lifestyle, and psychological variables. The modeling approach is based on linear regression, with Lasso regularization playing a central role in feature selection and predictive accuracy.

## Repository Structure
student-exam-score-prediction/
├── student_habits_performance.csv # Input dataset (must be in the same folder)
├── Project_Students_Score.ipynb # Jupyter notebook with full data science cycle
├── requirements.txt # Required Python libraries
└── README.md # Project overview and usage instructions

## Final Model Summary
- **Model Used:** `Lasso(alpha=0.1, selection='cyclic', fit_intercept=True, max_iter=10000)`
- **Final R² Score:** `0.8997` on the hold-out test set
- **Key Features Identified:**
  - Study Time (hr/day)
  - Mental Health Score
  - Sleep and Exercise Habits
  - Screen Time (e.g., Social Media, Netflix)

## Dataset
- **Title:** Student Habits vs Academic Performance  
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance)
- **License:** Apache License 2.0  
- **File required:** `student_habits_performance.csv` (must be in the same folder as the notebook)

## Installation
Clone the repo and install the required packages:
```bash
git clone https://github.com/your-username/student-exam-score-prediction.git
cd student-exam-score-prediction
pip install -r requirements.txt
