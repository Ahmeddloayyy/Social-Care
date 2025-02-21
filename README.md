# Predictive Modelling in Social Care

## 📝 Description  
This project leverages machine learning to predict care home effectiveness ratings using inspection data from children's social care facilities. By analyzing key variables such as leadership quality and safeguarding policies, the study aims to provide actionable insights for improving care quality. Two models—**Random Forest** and **Logistic Regression**—were developed and compared, with Random Forest achieving superior performance (80% accuracy).

---

## 🎯 Key Objectives  
1. **Predict effectiveness ratings** of care homes using machine learning.  
2. **Evaluate and compare** Random Forest and Logistic Regression models.  
3. **Identify critical features** influencing inspection outcomes (e.g., safeguarding, leadership).  
4. **Provide actionable recommendations** for stakeholders to enhance care quality.

---

## 📊 Dataset  
**Source**: [UK Children's Social Care Inspections and Outcomes](https://www.data.gov.uk/dataset/a2bd53f4-48b9-47b3-b994-1d8a380947c9/children-s-social-care-inspections-and-outcomes)  
**Size**: 1,477 records, 20 columns.  
**Key Features**:  
- `Overall Effectiveness` (Target Variable)  
- `Safeguarding Children`  
- `Leadership and Management`  

---

## 🔧 Methodology  
1. **Data Cleaning**:  
   - Imputed missing values, removed duplicates, and dropped irrelevant columns.  
2. **Exploratory Data Analysis (EDA)**:  
   - Correlation analysis and Tableau dashboard for visualization.  
   - Identified `Safeguarding Children` (0.75 correlation) and `Leadership` (0.70 correlation) as top predictors.  
3. **Model Development**:  
   - **Random Forest**: Handled non-linear relationships and class imbalance.  
   - **Logistic Regression**: Baseline model with SMOTE for class balancing.  

---

## 🛠 Technologies Used  
- **Python**: Pandas, Scikit-learn, NumPy (for data preprocessing and modeling).  
- **Tableau**: Geographic spread and distribution visualizations.  
- **Jupyter Notebook**: Code execution and analysis.  

---

## 📈 Results  
### Model Comparison  
| Metric               | Random Forest | Logistic Regression |  
|----------------------|---------------|---------------------|  
| **Accuracy**         | 80%           | 43%                 |  
| **Precision (Macro)**| 44%           | 37%                 |  
| **Recall (Macro)**   | 42%           | 43%                 |  

### Key Findings  
- Random Forest excelled in handling non-linear data and class imbalance.  
- Logistic Regression struggled due to linear assumptions and noise from SMOTE.  
- **Safeguarding Children** and **Leadership** were validated as critical predictors.  

---

## 🚀 Future Work  
- Expand feature set with geographic/socio-economic data.  
- Test advanced models (e.g., XGBoost, Neural Networks).  
- Optimize hyperparameters using Grid Search.  
- Address class imbalance with techniques like ADASYN.  

---

## 📚 References  
- Deng et al. (2024): Efficacy of Random Forest in healthcare analytics.  
- Sahoo et al. (2019): Exploratory data analysis best practices.  
- Full references listed in the report.  

---

## 🙏 Acknowledgments  
**Supervisor**: Raza Hasan  
**Dataset Providers**: UK Government Open Data Portal  

---

## 📜 License  
This project is open-source under the [MIT License](LICENSE).  

---

*For detailed analysis, methodology, and visualizations, refer to the full report.*  
