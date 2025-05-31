# 🚢 Titanic Dataset - Data Cleaning & Preprocessing

## 📁 Dataset
We used the [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset) to practice data cleaning and preprocessing tasks essential for any machine learning workflow.

---

## 🎯 Objective
Prepare raw data for machine learning by:
- Handling missing values
- Encoding categorical variables
- Scaling features
- Removing outliers

---

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Steps Performed

### 1. Data Exploration
- Used `.info()`, `.describe()`, and `.isnull().sum()` to understand data structure and missing values.

### 2. Handling Missing Data
- Filled `Age` with median.
- Filled `Embarked` with mode.
- Dropped `Cabin` due to high missing rate.

### 3. Encoding Categorical Variables
- Label encoded `Sex` (Male/Female → 1/0).
- One-hot encoded `Embarked` and dropped the first dummy variable to avoid multicollinearity.

### 4. Feature Scaling
- Standardized `Age` and `Fare` using `StandardScaler`.

### 5. Outlier Detection and Handling
- Visualized outliers using boxplots.
- Removed extreme values from `Fare` (e.g., values above 300) to reduce skew.

---

## ✅ Final Features
Cleaned dataset includes:
- Numerical: Age, Fare, Pclass, SibSp, Parch
- Encoded: Sex, Embarked_Q, Embarked_S
- Target (if for ML): Survived

---

## 📦 Output
A cleaned version of the dataset is saved as:
