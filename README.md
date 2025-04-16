# FCDS-Projects
A collection of data science projects completed as part of the FCDS . 

# project 1 : Predicting Student Performance and Passenger Survival: A Supervised Learning Approach

This project explores **two major areas of supervised learning**:

1. 🔁 **Regression Analysis** on a student performance dataset.
2. ✅ **Classification** using logistic regression on the Titanic survival dataset.

It includes complete **EDA**, **data preprocessing**, **modeling**, **visualization**, and **evaluation**.

---

## 📁 Datasets Used

### 1. 🎓 Student Performance Dataset
- **Source**: UCI Machine Learning Repository
- **Goal**: Predict students' final grades (`G3`) using features like past performance, family background, and lifestyle.

### 2. 🚢 Titanic Survival Dataset
- **Source**: [Kaggle Titanic Dataset]([https://www.kaggle.com/c/titanic/data](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams))
- **Goal**: Predict whether a passenger survived based on demographics and ticket information.

---

## 📌 Project Tasks

### 🧮 Part 1: Regression Models – Predict Student Final Grade (G3)

#### 1. Exploratory Data Analysis (EDA)
- Cleaned the dataset, handled data types, and encoded categorical variables.
- Visualized:
  - Histograms of grades, absences, and study time.
  - Correlation heatmap to identify features strongly related to `G3`.
  - Box plots for categorical variables.

#### 2. Preprocessing
- Selected numeric features based on correlation with `G3`.
- Encoded all categorical data and scaled features when needed.
- Split data into training and test sets (80/20).

#### 3. Simple Linear Regression
- Chose `G2` as the most correlated feature with `G3`.
- Fitted a model and plotted regression line.
- Evaluated using:
  - R² Score
  - Mean Squared Error (MSE)

#### 4. Multiple Linear Regression
- Used several predictors: `G1`, `G2`, `absences`, `studytime`, etc.
- Compared performance with the simple model.

#### 5. Polynomial Regression
- Applied polynomial regression (degrees 2, 3, 4) on `G2` to predict `G3`.
- Scaled polynomial features and visualized model fit.
- Compared models using R² and MSE.

---

### 🚦 Part 2: Logistic Regression – Titanic Survival

#### 1. Preprocessing
- Encoded categorical columns like `Sex`, `Embarked`.
- Handled missing values in `Age`, `Cabin`, and `Embarked`.
- Scaled features where needed.
- Split the data into training and testing sets (80/20).

#### 2. Modeling
- Trained a **logistic regression model** to predict `Survived`.

#### 3. Evaluation
- Generated a confusion matrix.
- Calculated accuracy, precision, recall, and F1 score.
- Visualized the confusion matrix using Seaborn heatmap.

---

## 📷 Sample Visualizations

- 📈 Correlation heatmap of student features.
- 🧾 Regression line between `G2` and `G3`.
- 📦 Box plots showing grade distribution by gender, school support, internet, and more.
- 🔍 Confusion matrix for Titanic predictions.

> *(Make sure to include screenshots or `.png` files in an `images/` folder and reference them here)*
