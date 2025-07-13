# **Predicting-Employee-Resignations-Using-Data-Science-and-HR-Analytics**

This project focuses on predicting employee attrition using machine learning techniques. It analyzes key factors influencing attrition and builds a classification model to identify employees at risk of leaving the organization. The objective is to help HR professionals make data-informed decisions to improve retention strategies and workforce stability.

---

## 📊 Project Overview

- **Goal**: Predict which employees are likely to leave the company.
- **Dataset**: HR data containing employee demographics, job roles, income, promotion history, and more.
- **Approach**: Exploratory Data Analysis (EDA), machine learning model building, evaluation, and deployment.

---

## 🧰 Tools & Technologies Used

- **Python**: Core programming language
- **Pandas & NumPy**: Data preprocessing and manipulation
- **Scikit-learn**: Machine learning model training and evaluation
- **Matplotlib & Seaborn**: Visualization and EDA
- **SHAP (optional)**: Model interpretability
- **Joblib**: Model serialization
- **Google Colab**: Development environment
- **Power BI**: (Optional) Dashboard integration

---

## 🔄 Project Pipeline

1. **Data Cleaning**: Removed irrelevant columns, handled nulls, and encoded categorical variables.
2. **Exploratory Data Analysis**: Investigated trends in attrition by department, salary, promotion timing, etc.
3. **Model Training**: Trained Logistic Regression and Decision Tree classifiers.
4. **Model Selection**: Evaluated performance using accuracy, precision, recall, and F1-score.
5. **Deployment**: Saved the best model and exported processed datasets for future use and visualization.

---

## 📈 Key Insights from EDA

- Employees in **Sales** and **Human Resources** exhibited higher attrition.
- **Lower salary bands** were associated with increased likelihood of leaving.
- **Frequent overtime** and **lack of recent promotion** were major drivers of attrition.

---

## ✅ Results

- **Best Model**: Decision Tree Classifier
- **Accuracy**: 76.4%
- **Recall (Attrition = Yes)**: 68%
- **Precision**: Balanced across both classes
- Visual assets such as confusion matrix and EDA plots included in the project outputs.

---

## 📁 Output Files

- `best_model.pkl`: Trained model saved for reuse
- `metrics.txt`: Model evaluation report
- `confusion_matrix.png`: Model confusion matrix
- `eda_*.png`: EDA visualizations (department, salary, promotion)
- `processed_hr_data.csv`: Preprocessed dataset for dashboard tools

---

## 📌 Recommendations

- Review salary structures for lower-income employees
- Improve promotion policies and transparency
- Monitor employee workload and overtime patterns
- Use predictive insights to proactively address potential attrition cases

---

## 🔒 Disclaimer

This project is intended for academic and learning purposes. All analysis and insights are based on publicly available or simulated data. The work presented here is original and developed in a professional data science workflow.

---

## 📝 Author

Maintained by [Your Name] – open to collaboration and feedback.

