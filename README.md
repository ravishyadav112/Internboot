<h1># Internboot
</h1>
# 🩺 Diabetes Prediction using Machine Learning

This project predicts the likelihood of diabetes in patients using various machine learning algorithms.  
The dataset contains medical attributes such as glucose level, BMI, age, and more, with the target variable **Outcome** (0 = Non-diabetic, 1 = Diabetic).

---

## 📂 Dataset
- **Source:** Pima Indians Diabetes Dataset (Kaggle/UCI)
- **Features:**
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
- **Target:** `Outcome` (0 or 1)

---

## ⚙️ Steps Performed
1. **Data Preprocessing**
   - Handled missing values (replaced invalid zeros with median).
   - Normalized numerical features.
   - Train-test split (80/20).

2. **Exploratory Data Analysis (EDA)**
   - Distribution plots of Glucose, BMI, and Age vs. Outcome.
   - Correlation heatmap to study feature relationships.

3. **Model Training**
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  
   - K-Nearest Neighbors (KNN)  
   - AdaBoost  

4. **Model Evaluation**
   - Accuracy score  
   - Confusion matrix  
   - Classification report  

---

## 📊 Results

| Model                | Accuracy |
|-----------------------|----------|
| Logistic Regression   | ~77%     |
| Decision Tree         | ~74%     |
| Random Forest         | **~79%** |
| K-Nearest Neighbors   | ~75%     |
| AdaBoost              | ~77%     |

✅ **Best Model:** Random Forest (79% accuracy)

---

## 📌 Insights
- Higher **glucose levels** strongly correlate with diabetes.  
- **BMI** and **Age** are also significant indicators.  
- Random Forest outperformed other models, showing robustness for medical datasets.  
- Feature scaling improved KNN and Logistic Regression performance.  
