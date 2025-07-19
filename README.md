# Salifort Motors Employee Attrition Analysis

This project is the capstone for Course 7 of the Google Advanced Data Analytics Certificate. The goal is to identify patterns in employee attrition at Salifort Motors and build predictive models to help the company retain talent.

---

## Overview

Using a real-world HR dataset, we explored factors influencing employee turnover, including satisfaction level, average monthly hours, promotions, salary levels, department, and more. After a detailed exploratory data analysis (EDA), we built and evaluated multiple machine learning models to predict whether an employee is likely to leave.

---

## Objective

- Analyze key features related to employee attrition.
- Identify trends using EDA and visualizations (box plots, heatmaps, scatter plots, etc.).
- Build classification models (Logistic Regression, Random Forest, XGBoost).
- Evaluate models using metrics such as Accuracy, Precision, Recall, F1-Score.
- Provide business recommendations based on data insights.

---

## Tools & Technologies

- **Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost)**
- **Jupyter Notebook**
- **Tableau** (for dashboard creation)
- **GitHub** (for version control and collaboration)

---

## Key Insights

- Low satisfaction levels and high monthly work hours were common among employees who left.
- Employees with no promotions over the last 5 years were more likely to leave.
- Employees in sales and technical departments showed higher attrition.
- Lower salary tiers had the highest turnover rates.

---

## Model Performance
```
| Model             | Accuracy | Precision | Recall | F1 Score |
|------------------|----------|-----------|--------|----------|
| Logistic Regression | 83%     | Low for attrition | Low | Low |
| Random Forest     | 97.8%    | High      | High   | High     |
| XGBoost           | **97.9%**| High      | High   | High     |
```

XGBoost yielded the best performance overall with balanced accuracy, recall, and precision.

---

## Visualizations

- **Box plots**: Highlighted spread and outliers in key numeric variables.
- **Histograms**: Showed distributions of satisfaction, hours, and time at company.
- **Heatmap**: Illustrated correlations between all variables.
- **Scatter plot**: Revealed clusters of low satisfaction & high hours leading to attrition.

---

## How to Run

Clone this repository:
```
   git clone https://github.com/your-username/salifort-attrition-analysis.git
   cd salifort-attrition-analysis
```

Use Jupyter notebook or Google Colab. 

## Future Improvements

- Implement feature selection techniques to reduce dimensionality.
- Add more demographic data (age, education) for richer analysis.
- Build an interactive dashboard in Tableau or Plotly for stakeholders.
- Test models with cross-validation and fine-tuned hyperparameters.

## License
This project is part of the Google Advanced Data Analytics Capstone. Github repository under MIT License. 

## Author
Asifur Rahman
University of Arizona | Google Data Advanced Data Analytics Capstone | 2025
LinkedIn: https://www.linkedin.com/in/iamasiff/
