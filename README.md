# Overstimulation-Analysis-Behavioral-and-Lifestyle-Insights

## 📌 Project Overview

This project investigates the relationship between behavioral, lifestyle, and psychological features and their impact on **overstimulation**. Using a dataset of 2,000 individuals, the analysis combines **exploratory data analysis**, **statistical correlation**, and **machine learning** to identify key predictors of overstimulation and provide actionable recommendations for improving mental well-being.

---

## 📊 Dataset Summary

- **Total Records:** 2,000
- **Features:** 19 predictor variables + 1 target variable (`Overstimulated`)
- **Target:** Binary (0 = Not Overstimulated, 1 = Overstimulated)

---

## 🔍 Key Deliverables

### 1. Data Exploration & Cleaning
- Handled missing values (none detected)
- Removed duplicates (none found)
- Treated outliers using IQR clipping
- Generated visualizations for distributions

### 2. Statistical & Correlation Analysis
- Identified strongest correlations:
  - **Screen Time:** +0.445
  - **Sleep Hours:** -0.403
  - **Stress Level:** +0.277
- Conducted hypothesis tests to validate relationships

### 3. Machine Learning Models
Trained and evaluated three classification models:
- **Logistic Regression:** 81% accuracy
- **Decision Tree:** 99% accuracy (risk of overfitting)
- **Random Forest:** 99% accuracy (more robust)

Top Predictive Features:
- Screen Time
- Sleep Hours
- Stress Level

### 4. Insights & Recommendations
- Reduce screen time and improve sleep hygiene
- Manage stress with mindfulness and regular breaks
- Encourage moderate physical activity
- Use tech-tracking tools to regulate usage

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `overstimulation_analysis.py` | Complete Python script (EDA, preprocessing, modeling) |
| `Overstimulation_Analysis_Final_Report.docx` | Final report including results, insights, and recommendations |
| `README.md` | Project summary and documentation |
| `requirements.txt` | (Optional) List of required Python packages |

---

## ⚙️ Technologies Used

- Python
- pandas, NumPy, seaborn, matplotlib
- scikit-learn
- imbalanced-learn (`RandomUnderSampler`)
- SciPy (correlation & hypothesis testing)

---

## ✅ Conclusion

The findings show that **behavioral factors** like excessive screen time, poor sleep, and high stress levels are the most influential contributors to overstimulation. By targeting these areas, individuals can take meaningful steps toward reducing cognitive overload and improving mental wellness.

---

## 📬 Contact

Developed by **Tolulope Emuleomo**  
📧 Email: tolulope.emuleomo@outlook.com 
📞 Phone: +2347038468202  

---
