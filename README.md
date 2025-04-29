# 🎓 Graduate Admission Prediction using Linear Regression

This project explores admission prediction for graduate programs using applicant data from Jamboree Education. The analysis focuses on identifying key academic indicators that influence admission chances using Linear, Ridge, and Lasso regression techniques.

## 📁 Project Files

- `README.md`: Project overview, objectives, key results, and insights.
- `Jamboree_Education_Linear_Regression.ipynb`: Full implementation in Python including EDA, model building, assumption testing, and evaluation.

## 🎯 Objective

To build and evaluate regression models that estimate students' chances of admission based on GRE scores, TOEFL scores, CGPA, SOP, LOR, research experience, and university rating.

## 📊 Tools & Libraries

- **Python** (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, Statsmodels)
- **Jupyter Notebook**

## ✅ Key Highlights

- Achieved **R² = 0.82** using Linear and Ridge Regression on both training and test datasets.
- Identified **CGPA, GRE, TOEFL, LOR, and Research** as statistically significant predictors.
- Reduced **Mean Absolute Error (MAE)** to **0.042**.
- Verified model assumptions: **No multicollinearity (VIF < 5)**, linearity, and homoscedasticity.
- Suggested enhancements for SOP and University Rating metrics due to low significance.

## 📌 Conclusion

This project demonstrates how data-driven approaches can support admissions decision-making. Insights from this model can be used by students to prioritize focus areas and by institutions to streamline applicant evaluation.
