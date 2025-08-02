#  Diabetes Prediction using Machine Learning

This project is a Machine Learning-based solution that predicts whether a person is diabetic or not, using medical data. It uses the popular **Pima Indians Diabetes Dataset** and applies supervised learning models to perform binary classification.

## Dataset Information

The dataset includes medical predictor variables and one target variable:
- **Pregnancies**
- **Glucose**
- **Blood Pressure**
- **Skin Thickness**
- **Insulin**
- **BMI**
- **Diabetes Pedigree Function**
- **Age**
- **Outcome (0 = Non-diabetic, 1 = Diabetic)**

Data Source: ['pima-data (1).xlsx']


##  Technologies Used

- Python 
- Pandas & NumPy
- Matplotlib & Seaborn for visualization
- Scikit-learn for ML models

---

## Project Steps

1. **Data Cleaning**: Handled missing/null values using `.isnull().sum()`
2. **Exploratory Data Analysis (EDA)**: Found patterns, distributions, and feature correlations
3. **Model Training**:
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier
4. **Model Evaluation**:
   - Confusion Matrix
   - Accuracy Score
   - ROC Curve

