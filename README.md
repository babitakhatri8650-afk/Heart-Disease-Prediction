# Heart Disease Prediction using Logistic Regression

## 📌 Project Description
This project predicts the 10-year risk of heart disease using the Framingham dataset and Logistic Regression.

## 📊 Dataset
- Framingham Heart Study Dataset
- Features: Age, BP, Cholesterol, Smoking, Diabetes, etc.
- Target: TenYearCHD (0 = No risk, 1 = Risk)

## ⚙️ Steps Performed
- Data Cleaning (handled missing values)
- Feature Scaling (StandardScaler)
- Train-Test Split (70-30)
- Model Building (Logistic Regression)
- Model Evaluation

## 📈 Results
- Accuracy: 83%
- Precision: 52%
- Recall: 7%
- F1-score: 0.12
- ROC-AUC: 0.72

## ⚠️ Conclusion
The model shows good accuracy but poor recall due to class imbalance. Improvements are needed to better detect heart disease cases.

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
