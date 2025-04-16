# IEEE CIS Selection Challenge 2025 – Diabetes Prediction

This repository contains my solution for the practical assessment of the **IEEE CIS (Computational Intelligence Society)** selection process at the **University of Brasília**, 2025 edition.

The challenge aimed to apply knowledge in **data science**, **statistics**, and **machine learning** to analyze clinical data and predict diabetes diagnoses in female patients from the Pima Indian heritage. The entire project was developed in Python using tools such as **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**, and **Scikit-Learn**.

---

## Technical Topics Covered

Throughout the challenge, the following concepts and techniques were applied:

- **Data Preprocessing**:
  - Detection and handling of missing values and outliers
  - Normalization and feature encoding

- **Statistical Analysis and Data Visualization**:
  - Histograms, boxplots, scatter plots, and descriptive statistics
  - Correlation analysis and hypothesis testing

- **Machine Learning Models**:
  - Logistic Regression
  - Decision Tree
  - Random Forest and XGBoost (experimental)

- **Feature Engineering**:
  - Variable transformation and creation of new features
  - Feature interaction analysis
  - Performance evaluation after feature engineering

- **Model Evaluation**:
  - Accuracy, confusion matrix, and feature importance analysis

---

## Challenge Questions

The assessment was structured into the following 11 questions:

1. Are there missing values or outliers in the dataset? How would you handle them?
2. How are the main variables (Glucose, BloodPressure, BMI, etc.) distributed? Use histograms and boxplots.
3. Is there a correlation between age and the presence of diabetes? Use statistical analysis and visualizations.
4. Which variables show the strongest correlation with diabetes diagnosis?
5. Is there a relationship between BMI and diabetes diagnosis? Compare groups statistically.
6. Is there a specific glucose level considered critical for diagnosis? Investigate with statistics and plots.
7. Train a decision tree model. What accuracy did you get? Discuss the results.
8. Is the DiabetesPedigreeFunction variable related to the presence of diabetes? Analyze it.
9. Do patients over 50 have higher diabetes rates? Compare to younger groups using statistics and plots.
10. Use logistic regression to estimate the probability of a diabetes diagnosis. Which variables influence it most?
11. What **feature engineering** techniques can improve prediction? Apply transformations and evaluate the impact.

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git

2. Open the main notebook IEEE_CIS_Challenge_2025.ipynb using Google Colab or Jupyter.

3. Make sure the following Python libraries are available: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## Files

`IEEE_CIS_Challenge_2025.ipynb`: Main notebook with all answers, comments, and visualizations.

`diabetes.csv`: Dataset used in the challenge
