# Titanic Survival Prediction using Naive Bayes

##  Project Overview
This project applies **Naive Bayes classification** to predict whether a passenger survived the Titanic disaster based on passenger details such as age, gender, class, and other features. The dataset used is the famous **Titanic dataset** from Kaggle.

The goal of this project is to demonstrate:
- Data preprocessing and feature engineering
- Building and training a Naive Bayes classifier
- Evaluating model performance with accuracy and classification metrics

---

##  Dataset
- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)
- **Features include:**
  - `Pclass` (Passenger class)
  - `Sex`
  - `Age`
  - `SibSp` (Number of siblings/spouses aboard)
  - `Parch` (Number of parents/children aboard)
  - `Fare`
  - `Embarked` (Port of embarkation)
- **Target Variable:** `Survived` (0 = No, 1 = Yes)

---

##  Steps in the Project
1. **Import libraries** – Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
2. **Load dataset** – Read the Titanic dataset  
3. **Data Cleaning**  
   - Handle missing values (Age, Embarked, etc.)  
   - Encode categorical variables (`Sex`, `Embarked`)  
   - Feature selection  
4. **Train-Test Split** – Divide dataset into training and testing sets  
5. **Model Building** – Train a **Naive Bayes Classifier**  
6. **Model Evaluation**  
   - Accuracy Score  
   - Confusion Matrix  
   - Classification Report  
7. **ROC, AUC curve**
---

##  Results
- Achieved **78% accuracy** 
- Model shows how gender and passenger class strongly influenced survival predictions  

---

## Technologies Used
- Python 3  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn

 ##  Install dependencies
 - pip install -r requirements.txt

## Run the Jupyter Notebook
- jupyter notebook Titanic-SurvivalPrediction-using-NAIVEBAYES.ipynb

## Future Improvements
- Try other classification models (Logistic Regression, Random Forest, XGBoost)
- Hyperparameter tuning
- Feature engineering (e.g., family size, title extraction)
---

##  How to Run the Project
1. Clone this repository  
   ```bash
   git clone https://github.com/yourusername/Titanic-SurvivalPrediction-using-NaiveBayes.git
