# 🎓 Graduate Admission Prediction using Linear Regression

This project explores admission prediction for graduate programs using applicant data from Jamboree Education. The analysis focuses on identifying key academic indicators that influence admission chances using Linear, Ridge, and Lasso regression techniques.

## 📁 Project Files

- `README.md`: Project overview, objectives, key results, feature descriptions, and insights.
- `Jamboree_Education_Linear_Regression.ipynb`: Full implementation in Python including EDA, model building, assumption testing, and evaluation.

## 🎯 Objective

To build and evaluate regression models that estimate students' chances of admission based on GRE scores, TOEFL scores, CGPA, SOP, LOR, research experience, and university rating.

## 🧩 Feature Details

| Feature             | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| GRE Score           | GRE (Graduate Record Examination) score out of 340                         |
| TOEFL Score         | TOEFL (Test of English as a Foreign Language) score out of 120              |
| University Rating   | Rating of the university (scale: 1 to 5)                                    |
| SOP                 | Strength of Statement of Purpose (scale: 1 to 5)                           |
| LOR                 | Strength of Letter of Recommendation (scale: 1 to 5)                       |
| CGPA                | Undergraduate GPA (scale: 0 to 10)                                          |
| Research            | Research experience (1 = Yes, 0 = No)                                       |
| Chance of Admit     | Estimated probability of admission (target variable, scale: 0 to 1)         |

## 📊 Tools & Libraries

- **Python** (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, Statsmodels)
- **Jupyter Notebook**

## ✅ Key Highlights

- Achieved **R² = 0.82** using Linear and Ridge Regression models on both training and test datasets.
- Identified **CGPA, GRE, TOEFL, LOR, and Research experience** as statistically significant predictors.
- Reduced **Mean Absolute Error (MAE)** to **0.042** for high prediction accuracy.
- Verified model assumptions: **No multicollinearity (VIF < 5)**, linearity, and homoscedasticity.
- Suggested enhancing data quality around **SOP** and **University Rating** for future model improvement.

## 📌 Conclusion

This project demonstrates how data-driven approaches can support graduate admission decisions. Insights from this model can guide students to prioritize academic and research strengths and help institutions optimize admission processes.
