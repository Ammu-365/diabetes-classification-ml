# Diabetes Classification using Machine Learning

## 📌 Project Overview
This project predicts the likelihood of diabetes in patients based on clinical diagnostic metrics. It was completed as a Major Project for the Bachelor of Science in Computer Science during a Data Science internship at Dexterity Global.

## 📊 Dataset
The dataset (`diabetes.csv`) contains 768 entries with 9 features including Glucose, Blood Pressure, BMI, Insulin, and Age. 
- **Target Variable:** `Outcome` (1 = Diabetic, 0 = Non-Diabetic)

## ⚙️ Methodology
1. **Data Preprocessing:** Replaced invalid zeros in critical columns (Glucose, BloodPressure, SkinThickness, Insulin, BMI) with the mean.
2. **Feature Scaling:** Applied `StandardScaler` to standardize features.
3. **Data Split:** 80% Training, 20% Testing.
4. **Models Trained:** 
   - Logistic Regression
   - Random Forest Classifier

## 📈 Results
| Model | Accuracy | Precision | Recall | F1-Score |
|---|---|---|---|---|
| Logistic Regression | 75.32% | 66.67% | 61.82% | 64.15% |
| Random Forest | 75.32% | 65.45% | 65.45% | 65.45% |

**Conclusion:** While both models achieved similar accuracy, Logistic Regression showed a better balance in recall and F1-score, making it more suitable for medical contexts where minimizing false negatives is critical.

## 📁 Files in this Repository
- `diabetes.pdf` - Full Project Report
- `diabetes_classification.py` - Python source code
- `diabetes.csv` - Dataset
- `requirements.txt` - Required Python libraries

## 👤 Author
**Mellam Lahari**  
Internship on Data Science conducted by Dexterity Global
