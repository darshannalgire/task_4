 Titanic Survival Prediction - Logistic Regression

This project predicts whether a passenger survived the Titanic disaster using **Logistic Regression**.  
The dataset comes from the famous **Kaggle Titanic dataset**.

---

 Steps Followed

 1. Data Loading
- Loaded `train.csv` dataset using Pandas.
- Previewed first few rows.
  Screenshot: Data Preview (`df.head()`) 
 2. Data Cleaning
- Checked for missing values (`df.isnull().sum()`).
- Filled missing values:
  - `Age` → median
  - `Embarked` → most frequent value

 Screenshot: Missing values before and after cleaning

---

 3. Feature Encoding
- Converted categorical columns (`sex`, `embarked`) into numeric using **One-Hot Encoding**.

 *Screenshot: Encoded dataframe head*

---

 4. Splitting Data
- Split dataset into **train and test sets** (80%-20%).

---

 5. Model Training
- Used Logistic Regression from `scikit-learn`.
- Trained the model on training data.

---

 6. Model Evaluation
- Evaluated using:
  - Accuracy Score
  - Confusion Matrix
