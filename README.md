# Loan Prediction - Credit Risk Classification

This project predicts whether a loan applicant is likely to default or not using supervised machine learning techniques. The dataset used is the **Loan Prediction Problem Dataset** from Kaggle.

##  Dataset

- `train.csv` — Contains loan application data along with the loan approval status (`Loan_Status`).
- [Download from Kaggle](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)

##  Objective

Build a classification model to predict `Loan_Status` (Y/N) based on features like:
- Applicant’s income
- Loan amount
- Education
- Credit history
- Marital status, etc.

---

##  Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

##  Steps Performed

### 1. **Data Loading and Overview**
- Loaded `train.csv` using Pandas.
- Checked dataset structure and sample values.

### 2. **Missing Value Handling**
- Filled missing categorical values using **mode**.
- Filled numerical values using **median**.

### 3. **Exploratory Data Analysis (EDA)**
- Plotted histograms and scatterplots:
  - Loan amount distribution
  - Applicant income vs loan amount
  - Loan approval by education level

### 4. **Data Preprocessing**
- Dropped unnecessary ID column.
- Encoded categorical features using `LabelEncoder`.

### 5. **Model Building**
- Split data into training and testing sets.
- Trained two models:
  - Logistic Regression
  - Decision Tree Classifier

### 6. **Model Evaluation**
- Evaluated accuracy on test data.
- Displayed confusion matrix for Logistic Regression.

---

##  Results

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| ~[Varies depending on random state] |
| Decision Tree      | ~[Varies depending on split]        |

> Logistic Regression often performs slightly better due to generalization.

---

##  How to Run

1. Upload `train.csv` in Google Colab or your Jupyter environment.
2. Run each cell in the provided notebook.
3. Ensure required libraries are installed (`!pip install seaborn scikit-learn` if needed).

---

##  Links

- [Original Dataset](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)
- [Google Colab](https://colab.research.google.com/) — Recommended for running this notebook.

---

##  Author

**Farah Afsar**  
Project: Credit Risk Prediction
