# Student Exam Score Prediction

This project focuses on predicting student exam performance using behavioral, lifestyle, and psychological variables. The modeling approach is based on linear regression, with Lasso regularization playing a central role in feature selection and predictive accuracy.

## Repository Structure

├── README.md # Project overview and usage instructions 
├── Project_Students_Score.ipynb # Jupyter notebook with full data science cycle 
├── Student_Performance_Project_Report.pdf # Technical report summarizing project, modeling pipeline, results, and practical recommendations
├── requirements.txt # Required Python libraries 
└── student_habits_performance.csv # Input dataset (must be in the same folder as Project_Students_Score.ipynb)

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
```

## Notebook Contents
The Jupyter Notebook includes:
- Introduction
- Preparation
- Data Overview
- Data Cleaning and Preparation
- Modeling
- Finalization and Deployment

## Deployment Potential

The final model is ready for deployment in educational analytics systems.  
It offers interpretable insights into which academical and behavioral factors have most influence on student performance.

