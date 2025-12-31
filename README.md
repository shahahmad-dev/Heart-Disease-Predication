

# Heart Disease Prediction Project 🫀

## Overview

This project focuses on **predicting heart disease severity** using patient data.
The goal is to classify patients into **5 categories of heart disease**:

| Value | Description            |
| ----- | ---------------------- |
| 0     | No heart disease       |
| 1     | Mild heart disease     |
| 2     | Moderate heart disease |
| 3     | Severe heart disease   |
| 4     | Critical heart disease |

We performed **exploratory data analysis (EDA)**, handled missing values and outliers, and built **multi-class classification models** to predict heart disease.

---

## Dataset

The dataset contains patient information including:

* Age
* Gender
* Chest pain type (`cp`)
* Blood pressure (`trestbps`)
* Cholesterol (`chol`)
* Maximum heart rate (`thalach`)
* Exercise-induced angina (`exang`)
* ST depression (`oldpeak`)
* And more features

**Data Sources:** Publicly available heart disease datasets.

---

## Steps Performed

1. **Data Exploration**

   * Checked **age, gender, and region patterns**.
   * Calculated **mean, median, and mode** for key columns.
   * Visualized feature distributions and relationships.

2. **Missing Values Imputation**

   * Numerical columns: Imputed using **Iterative Imputer / Median**
   * Categorical columns: Imputed using **Mode**

3. **Outlier Treatment**

   * Detected using **IQR method** and visualized with **boxplots**
   * Removed errors and retained meaningful extreme values

4. **Feature Analysis**

   * Identified strong predictors such as **chest pain, cholesterol, blood pressure, and exercise-induced angina**.

5. **Model Building**

   * Multi-class classification models used:

     * Logistic Regression
     * K-Nearest Neighbors (KNN)
     * Naive Bayes (NB)
     * Support Vector Machine (SVM)
     * Decision Tree
     * Random Forest
     * XGBoost
     * Gradient Boosting
     * AdaBoost
     * LightGBM

6. **Model Evaluation**

   * Evaluated using **accuracy, classification reports, and confusion matrices**
   * Ensemble models (Random Forest, XGBoost, LightGBM) performed best

---

## Key Findings

* **Middle-aged patients** (50–55 years) are at higher risk.
* **Chest pain type** is a strong indicator of heart disease severity.
* **Ensemble models** provide the best performance for multi-class classification.
* Gender imbalance: **Males (78.91%)** vs **Females (21.09%)**

---

## How to Run

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```
2. Install required libraries:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook Heart_Disease_Prediction.ipynb
   ```

---

## Libraries Used

* Python 3.x
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* XGBoost, LightGBM

---

## Author

**Shah Ahmad Noorani**
Data Science Enthusiast | Machine Learning | AI

