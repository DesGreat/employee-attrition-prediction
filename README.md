# Employee Attrition Prediction – Hackathon Solution
 End-to-end machine learning solution for predicting employee attrition using EDA, feature engineering, and classification models.

**🏆 Final Score: 0.87137 – DSN Lekki–Ajah Hackathon**  
**🥉 Placed: Top 3 (2nd Runner-Up)**  

This repository contains my end-to-end machine learning solution for the **DSN Lekki–Ajah Employee Attrition Prediction Hackathon**, where I placed **Top 3** with a final leaderboard score of **0.87137**.  
This was my **first ever machine learning hackathon**, and a major milestone in my learning journey.

The goal of the challenge was to predict which employees are likely to leave a company based on their demographic, behavioral, and workplace-related characteristics.

---

## 🚀 Project Overview  

Employee attrition is a major challenge for organizations.  
This project explores key factors behind employee turnover and builds predictive models using:

- ✔ Comprehensive EDA  
- ✔ Feature engineering & preprocessing  
- ✔ Handling class imbalance  
- ✔ Multiple machine learning models  
- ✔ Model evaluation & comparison  
- ✔ Insights for HR decision-making  

---

## 🏆 Hackathon Results  
- 🥉 **Top 3 (2nd Runner-Up)**  
- 📊 **Final Score:** *0.87137*  
- 📍 **Event:** DSN Lekki–Ajah Hackathon  
- 🧠 **Task:** Binary Classification – Predict Employee Attrition  

---

## 🧠 Key Insights From the Data  

Major factors influencing attrition included:

- Employees working **OverTime** had significantly higher attrition  
- Employees with **lower monthly income** tended to leave more  
- **Job role**, **job satisfaction**, and **work-life balance** were strong indicators  
- **Age** and **years at company** also contributed to turnover risk  

These insights informed model interpretation and HR recommendations.

---

## 🤖 Models Used & Performance Summary  

### **1️⃣ Logistic Regression (Final Model)**  
- Best **recall** for attrition class  
- Best balance of **false positives vs false negatives**  
- Highly **interpretable** for HR stakeholders  
- Selected as **final model**

### **2️⃣ Random Forest**  
- Good accuracy  
- Poor recall for minority class  
- Not ideal for imbalanced HR data

### **3️⃣ XGBoost**  
- Strong performance  
- Better recall than Random Forest  
- Still not as effective as Logistic Regression for business impact

---

## 🛠 Tech Stack  
- **Python**  
- **Pandas**, **NumPy**  
- **Scikit-Learn**  
- **Matplotlib**, **Seaborn**  
- **XGBoost**  

---

## 📁 Repository Structure  

```
employee-attrition-prediction/
│
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
│
├── notebooks/
│   ├── Employee_Attrition_Prediction.ipynb
│   ├── Employee_Attrition_Prediction.html
│   └── Employee_Attrition_Prediction.pdf
│
├── reports/
│   └── README.md
│
├── images/
│   └── README.md
│
└── src/
    └── README.md
```

---

## 📥 Getting Started  

### **Clone the Repository**
```bash
git clone https://github.com/DesGreat/employee-attrition-prediction.git
```

### **Install Dependencies**
```bash
pip install -r requirements.txt
```

### **Open the Notebook**
```bash
jupyter notebook
```

---

## 📘 Future Improvements  
- Hyperparameter tuning (GridSearchCV, Optuna)  
- SHAP-based interpretability  
- Streamlit app for deployment  
- Modular Python scripts (preprocessing, training, evaluation)  
- CI/CD workflow + automated testing  

---

## 🙏 Acknowledgements  
Special thanks to **Data Scientists Network (DSN)** for organizing the hackathon  
and to the amazing community that supports continuous learning.

---

## 🔗 Connect With Me  
- **GitHub:** https://github.com/DesGreat  
- **LinkedIn:** [https://www.linkedin.com/in/destiny-aimufia14](https://www.linkedin.com/in/destiny-aimufia14)

