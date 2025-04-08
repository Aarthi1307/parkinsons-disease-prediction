# 🧠 Parkinson's Disease Prediction

This project uses machine learning techniques to predict whether a person has Parkinson's disease based on voice measurements. It explores three classifiers—**SVM**, **Random Forest**, and **K-Nearest Neighbors (KNN)**—with hyperparameter tuning, cross-validation, and performance evaluation using accuracy, confusion matrix, classification report, and ROC curves.

---

## 📁 Dataset

The dataset used is **Parkinsson disease.csv**, which includes biomedical voice measurements from patients with and without Parkinson’s disease. Each row represents one voice recording and includes 22 features.

- Target variable: `status`
  - `1` = Parkinson's
  - `0` = Healthy

---

## 🛠️ Methods Used

- Data Preprocessing & Standardization
- Train-Test Split
- GridSearchCV for Hyperparameter Tuning
- Cross-Validation (5-Fold)
- Evaluation:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report
  - ROC Curve with AUC Score
- Visualization of model comparisons
- Prediction for new patient data

---

## 📊 Models Compared

- **Support Vector Machine (SVM)**
- **Random Forest Classifier**
- **K-Nearest Neighbors (KNN)**

All models were tuned and compared based on their test set accuracy and AUC.

---

## 📈 Output Example

```bash
Tuned SVM Test Accuracy: 0.94
The person HAS Parkinson's disease.
