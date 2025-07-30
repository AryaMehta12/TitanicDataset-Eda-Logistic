# 🚢 Titanic Dataset – EDA & Logistic Regression

This project explores the famous [Titanic dataset](https://www.kaggle.com/competitions/titanic) from Kaggle and builds a **Logistic Regression model** to predict passenger survival. It includes full **Exploratory Data Analysis (EDA)**, **feature engineering**, and **model evaluation**, achieving a public leaderboard accuracy of **77.03%**.

---

## 📌 Project Highlights

- Cleaned and explored Titanic training data
- Engineered features like title extraction, cabin grouping, and ticket transformation
- Encoded categorical variables using `OneHotEncoder`
- Scaled numerical features using `StandardScaler`
- Trained a `LogisticRegression` classifier
- Generated a valid Kaggle submission (`submission.csv`)

---

## 🗂️ Folder Structure

TitanicDataset-Eda-Logistic/
├── titanic_eda.ipynb # Full analysis and model notebook
├── submission.csv # Final predictions for Kaggle submission
├── train.csv # Training dataset (optional to upload)
├── test.csv # Test dataset (optional to upload)
└── README.md # This file


---

## 🚀 How to Run

1. **Clone the repository**

```bash
git clone https://github.com/AryaMehta12/TitanicDataset-Eda-Logistic.git
cd TitanicDataset-Eda-Logistic
```
2. **Install dependecies**
pip install pandas numpy scikit-learn matplotlib seaborn

3. **Run the notebook**
jupyter notebook titanic_eda.ipynb

4. **Download the data**
   Make sure train.csv and test.csv are present in the directory. You can download them from the Kaggle Titanic competition page.

📊 Model Performance
Algorithm: Logistic Regression

Public Kaggle Score: 0.7703 (77.03%)

Evaluation Metric: Accuracy

🔧 Feature Engineering
Extracted titles from names (e.g., Mr, Miss, etc.)

Created binary flags for Cabin availability and multiple cabins

Transformed ticket values (e.g., numeric vs. non-numeric)

Encoded categorical columns with OneHotEncoder

Scaled numeric columns with StandardScaler

