# 🎓 AI-Driven Student Performance Prediction Dashboard

This project is a data-driven analytics and prediction system designed to forecast student academic performance using internal assessment data, attendance records, and historical academic trends.

---

## 📌 Problem Statement

Educational institutions often identify struggling students only after significant academic decline, leaving little room for timely intervention. This project addresses that gap by developing a predictive system that leverages historical and behavioral data to proactively assess performance risks and guide academic decisions.

---

## 🎯 Objectives

- Build a predictive model to forecast student academic performance
- Visualize key academic and behavioral trends
- Provide actionable insights for educators and administrators
- Deploy an interactive dashboard for real-time analytics and model interaction

---

## 📊 Dataset Overview

Features include:
- Attendance records (percentage)
- Internal assessment scores
- Previous exam scores
- Sleep hours, physical activity, study hours
- Lifestyle indicators (stress, social interaction, etc.)

Target:
- `Exam_Score` (for regression)
- `Performance` (derived classification: Good / Average / Poor)

---

## 🔍 Key Features

- Data preprocessing, cleansing, and exploratory analysis
- Correlation and feature impact assessment
- Classification & regression modeling using:
  - Decision Trees
  - Logistic Regression
  - Random Forest
- Performance evaluation metrics (accuracy, F1-score, confusion matrix)
- Visualizations using Seaborn, Matplotlib, and Plotly
- Interactive dashboard (Streamlit or Plotly Dash planned)

---

## ⚙️ Tech Stack

- **Languages**: Python (3.10+)
- **Libraries**:
  - Pandas, NumPy, Scikit-learn
  - Seaborn, Matplotlib, Plotly
  - XGBoost (optional)
- **Tools**:
  - Jupyter Notebooks
  - Streamlit or Dash (dashboard)
  - Git & GitHub (version control)

---

## 🚀 Getting Started

### 1. Clone the Repository
bash
git clone https://github.com/yourusername/ai-student-performance.git
cd ai-student-performance

---

### 📈 Model Overview

| Model               | Accuracy         | Comments                     |
| ------------------- | ---------------- | ---------------------------- |
| Decision Tree       | \~100% (Overfit) | Needs regularization         |
| Logistic Regression | TBD              | Baseline benchmark           |
| Random Forest       | TBD              | Ensemble performance pending |

---

### 📌 TODO

 - Implement SHAP/feature importance visualizations

 - Finalize dashboard with live model integration

- Add cross-validation and hyperparameter tuning

 - Unit test critical components

 - Dockerize for production deployment

---

### 🤝 Contribution

Contributions are welcome! Please fork the repo and submit a pull request. For major changes, open an issue to discuss what you’d like to change.



