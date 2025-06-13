
# 🛒 SuperKart Sales Prediction - Machine Learning Project (Linear Regresion)

Created a supervised learning model in Python using linear regression to predict sales trends across various store formats within a supermarket chain network called SuperKart.

---

## 📌 Summary Overview

We were given a structured dataset (in table format). The dependent/target variable to predict is "Product Store Sales Total" — a continuous value — making this a **supervised regression problem**.

We explored whether a **linear regression** model would be appropriate, or whether non-linear methods or transformations were required.

Key steps included:

- Exploratory Data Analysis (EDA): Checked correlations among features and between features and the target
- Linear Regression Criteria:
  - Residual analysis: mean of residuals ≈ 0
  - Homoscedasticity of residuals
  - Linearity of predictors wrt target
  - Normality of residuals (Gaussian distribution)

Once satisfied, we confirmed the linear model was appropriate for prediction.

---

## 📊 Key Deliverables

- Developed a regression model that explained ~79% of sales variation
- Generated store-specific insights and business recommendations
- Identified high-revenue categories and data collection gaps

---

## 🛠️ Tech Stack

- Python (Pandas, NumPy, statsmodels, Scikit-learn, Matplotlib, seaborn)
- Jupyter Notebook (Google Colab)

---

## 📂 Files

- `superkart_ml.ipynb`: Main notebook with code, visualizations, and model development
- `superkart_ml.html`: Exported HTML report (viewable without code)

---
