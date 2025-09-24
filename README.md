# 🦴 Detecting Orthopedic Anomalies with XGBoost 🦴

---

## About This Project 

This project builds a **binary classification model** to detect orthopedic anomalies from patient biometric data.  

- Model: **XGBoost**  
- Evaluation: sensitivity, specificity, accuracy, precision, and confusion matrix  
- Optimization: **Optuna** hyperparameter tuning with cross-validation  

💡 **Why it matters:** The goal is to accurately identify patients with anomalies so they can receive the right treatment. Reducing false negatives is critical in this medical context.

---

## 📊 Dataset

The data comes from a biomedical study by **Dr. Henrique da Mota**, GARO, Lyon, France.  

**Binary Classification Task (our focus):**  
- Normal (NO): 100 patients  
- Abnormal (AB): 210 patients (Disk Hernia + Spondylolisthesis)  

### Features
Each patient is described with **6 biomechanical attributes**:  

- Pelvic incidence  
- Pelvic tilt  
- Lumbar lordosis angle  
- Sacral slope  
- Pelvic radius  
- Degree of spondylolisthesis  

### Source
📂 [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Vertebral+Column)  
(Dua, D. & Graff, C., 2019)

---

## 🎯 Key Takeaways

- Hyperparameter tuning with **Optuna** improved model performance  
- High **true positive rate** ensures fewer patients with anomalies are missed  
- Threshold selection prioritized medical safety: better to flag healthy patients than miss someone who needs treatment  

---

## 🤗 Learnings

This project was a great way to practice **XGBoost, model evaluation, and hyperparameter tuning**.  
Hope it inspires your own experiments in **machine learning** and **medical data analysis**! 🚀
