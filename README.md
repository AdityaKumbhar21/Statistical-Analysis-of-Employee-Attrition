# Statistical Analysis of Employee Attrition

This project analyzes employee attrition using statistical methods and visualizations. By exploring key workplace features like age, distance from home, relationship satisfaction, and work-life balance, the goal is to identify patterns that contribute to employee turnover.

---

## 📁 Repository Structure

- `statistics_project.ipynb` – Main Jupyter Notebook with analysis, visualizations, and hypothesis testing
- `presentation/` – PowerPoint presentation summarizing the project
- `README.md` – This file

---

## 🎯 Objective

- Understand factors influencing employee attrition
- Use statistical tests (t-test, chi-square) to validate hypotheses
- Visualize correlations between workplace variables and attrition
- Derive actionable insights to reduce turnover

---

## 🧪 Statistical Techniques Used

| Variable                     | Test Used          | Hypothesis                                                | Result                  |
|-----------------------------|--------------------|------------------------------------------------------------|--------------------------|
| Age vs Attrition            | T-Test             | Age affects employee attrition                            | Significant            |
| Distance from Home vs Attrition | T-Test         | Distance affects employee attrition                       | Significant            |
| Work-Life Balance vs Attrition | Chi-Square Test | Work-life balance is associated with attrition            | Significant            |
| Relationship Satisfaction vs Attrition | Chi-Square Test | Relationship satisfaction influences attrition |  Not Significant        |
| Tenure vs Attrition         | Trend Analysis     | Longer tenure reduces likelihood of attrition             | Observed Pattern       |

---

## Visualizations

- **Bar Charts**:
  - Attrition vs Work-Life Balance
  - Attrition vs Relationship Satisfaction
- **Pie Chart**:
  - Attrition distribution across Age Groups and Tenure Groups
- **Histograms**:
  - Distance from Home grouped by Attrition
- **Line Chart**:
  - Age vs Attrition Count

---

## Key Insights

- Younger employees are more likely to leave.
- Employees living farther from the office show higher attrition.
- Work-life balance is significantly associated with attrition.
- Relationship satisfaction does **not** strongly influence attrition.
- Longer tenure suggests more employee loyalty and lower attrition.

---

## Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy.stats`

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AdityaKumbhar21/Statistical-Analysis-of-Employee-Attrition.git
