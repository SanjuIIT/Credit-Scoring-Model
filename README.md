# Credit Score Prediction using Machine Learning

## Project Overview
This project builds a **Credit Score Prediction System** to classify individuals into risk categories based on their financial history and behavioral features.  
Credit scoring is one of the most **critical applications of machine learning in finance**, helping banks and lenders assess loan eligibility, manage credit risks, and minimize defaults.  

The notebook (`CreditScoreModel.ipynb`) demonstrates a **full ML pipeline**: from raw data exploration to feature engineering, model training, and evaluation.

---

## Objectives
- Predict whether a customer has a **Good, Standard, or Poor Credit Score**.  
- Explore **financial features** like payment history, loan details, income, and other behavioral metrics.  
- Apply **ML classification algorithms** to achieve high prediction accuracy and interpretability.  

---

## Workflow / Pipeline
1. **Data Exploration & Cleaning**
   - Handled missing values and inconsistent entries.
   - Performed **EDA** (Exploratory Data Analysis) to understand distribution of credit scores.
   - Detected and treated outliers for stability.

2. **Feature Engineering**
   - Encoded categorical variables (e.g., occupation, payment behavior).
   - Scaled numeric features (e.g., income, loan amount, age).
   - Created derived features to enhance signal (e.g., debt-to-income ratio).

3. **Model Building**
   - Implemented multiple ML models:
     - Logistic Regression
     - Random Forest Classifier
     - Gradient Boosting (XGBoost / LightGBM)
   - Applied **hyperparameter tuning** to improve accuracy.

4. **Model Evaluation**
   - Used metrics like **Accuracy, Precision, Recall, F1-score**.
   - Analyzed **confusion matrix** to assess misclassifications.
   - Compared models for best performance trade-off between accuracy and interpretability.

5. **Insights & Business Impact**
   - Identified key financial indicators most predictive of creditworthiness.
   - Highlighted explainability for **regulatory compliance** in finance.

---

## Results
- Achieved **83.33% accuracy** on test data.  
- Gradient Boosting performed the best with balanced recall across classes.  
- Feature importance analysis showed:
  - **Payment history** and **Debt-to-Income Ratio** are top predictors.
  - Behavioral patterns like **delayed payments** directly impact credit score.

---

## ⚡ Key Features
- End-to-end **Credit Scoring ML pipeline**.  
- Handles **imbalanced classes** with proper resampling techniques.  
- Emphasizes both **accuracy & interpretability** (important in finance).  
- Modular notebook design → easy to adapt to real-world financial datasets.  

---

## 🛠️ Tech Stack
- **Language**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost/LightGBM  
- **Tools**: Jupyter Notebook
  
---

## Myself:
**Muthu Sanjay P - CE22B076**  
IIT Madras • Data/Analytics/ML Enthusiast  
Mail: ce22b076@smail.iitm.ac.in • [LinkedIn](https://www.linkedin.com/in/muthusanjay/)  • [GitHub](https://github.com/SanjuIIT)   

