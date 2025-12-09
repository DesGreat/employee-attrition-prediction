# Employee Attrition Prediction – Hackathon Solution  
End-to-end machine learning project for predicting employee attrition using EDA, feature engineering, and classification models.

---

## 🏆 Hackathon Achievement  
**Final Score:** 0.87137  
**Position:** 🥉 Top 3 (2nd Runner-Up)  
**Event:** DSN Lekki–Ajah Hackathon  
**Track:** Employee Attrition Prediction  

This repository contains my end-to-end machine learning solution for the DSN Lekki–Ajah Employee Attrition Prediction Hackathon, where I finished **Top 3** with a final score of **0.87137**.

This was my **first ever machine learning hackathon**, marking a major milestone in my Data Science journey.

The challenge aimed to predict which employees are likely to leave a company based on demographic, behavioral, and workplace-related characteristics.

---

## 🚀 Project Overview  
Employee attrition is a major challenge for organizations.  
This project analyzes and models the drivers of attrition using:

- ✔ Comprehensive EDA  
- ✔ Feature engineering & preprocessing  
- ✔ Handling class imbalance  
- ✔ Multiple machine learning models  
- ✔ Model comparison & evaluation  
- ✔ Insights for HR decision-making  

---

## 🧠 Key Insights From the Data  
Some major factors contributing to attrition include:

- Employees working **OverTime** showed significantly higher attrition  
- Employees with **lower monthly income** were more likely to leave  
- **Job role**, **job satisfaction**, and **work-life balance** were strong predictors  
- **Age** and **years at company** were major determinants  

These insights guided feature selection and supported HR recommendations.

---

## 🤖 Models Used & Performance Summary  

### 1️⃣ Logistic Regression (Final Model)  
- Best recall for the attrition class  
- Strongest balance of false positives vs false negatives  
- Highly interpretable for HR teams  
- **Selected as the final model**

### 2️⃣ Random Forest  
- Good overall accuracy  
- Weak recall for minority class  
- Not ideal for imbalanced HR datasets

### 3️⃣ XGBoost  
- Strong performance  
- Better recall than Random Forest  
- Still not as effective as Logistic Regression for business KPIs

---

## 🛠 Tech Stack  
- Python  
- Pandas, NumPy  
- Scikit-Learn  
- Matplotlib, Seaborn  
- XGBoost  

---

## 📁 Repository Structure  

employee-attrition-prediction/
│
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
│
├── notebooks/
│ ├── Employee_Attrition_Prediction.ipynb
│ ├── Employee_Attrition_Prediction.html
│ └── Employee_Attrition_Prediction.pdf
│
├── reports/
│ └── README.md
│
├── images/
│ └── README.md
│
└── src/
└── README.md

yaml
Copy code

---

## 📥 Getting Started  

### Clone the Repository
```bash
git clone https://github.com/DesGreat/employee-attrition-prediction.git
Install Dependencies
bash
Copy code
pip install -r requirements.txt
Open the Jupyter Notebook
bash
Copy code
jupyter notebook
📘 Future Improvements
Hyperparameter tuning (GridSearchCV, Optuna)

SHAP-based interpretability

Streamlit deployment app

Modular, production-ready Python scripts

CI/CD workflow and automated testing

🙏 Acknowledgements
Special thanks to Data Scientists Network (DSN) for hosting the hackathon
and to the amazing learning community that supported the journey.

🔗 Connect With Me
GitHub: https://github.com/DesGreat
LinkedIn: https://www.linkedin.com/in/destiny-aimufia14

yaml
Copy code
