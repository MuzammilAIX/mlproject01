# Student Performance Prediction

A machine learning project that analyzes student performance and builds regression models to predict **Math Scores** from demographic, educational, and academic features.

## Overview

This project follows a complete machine learning workflow:

* Data collection & validation
* Exploratory Data Analysis (EDA)
* Data preprocessing
* Feature transformation
* Model training
* Model evaluation
* Prediction

The dataset contains **1,000 student records** with features including gender, race/ethnicity, parental education, lunch type, test preparation, reading score, and writing score.

## Tech Stack

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

## Machine Learning

The project compares multiple regression algorithms:

* Linear Regression
* Ridge Regression
* Lasso Regression
* K-Neighbors Regressor
* Decision Tree Regressor
* Random Forest Regressor
* AdaBoost Regressor

Categorical features are encoded using **OneHotEncoder**, while numerical features are scaled using **StandardScaler**.

## Results

| Model             |    Test R² |
| ----------------- | ---------: |
| Ridge Regression  | **0.8806** |
| Linear Regression |     0.8804 |
| Random Forest     |     0.8524 |
| AdaBoost          |     0.8490 |
| Lasso             |     0.8253 |
| KNN               |     0.7835 |
| Decision Tree     |     0.7528 |

The final Linear Regression implementation achieved an R² score of approximately **88.04%** on the test set.

## Project Structure

```text
mlproject01/
│
├── artifacts/
├── notebook/
│   └── data/
├── src/
│   ├── component/
│   ├── pipeline/
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
│
├── requirements.txt
├── setup.py
└── README.md
```

## Run Locally

```bash
git clone https://github.com/MuzammilAIX/mlproject01.git
cd mlproject01

pip install -r requirements.txt
```

## Dataset

Student Performance in Exams dataset from Kaggle.

## Author

**Muhammad Muzammal Hussain**

Aspiring AI Engineer | Python Developer | Machine Learning • Deep Learning • LLMs

[GitHub](https://github.com/MuzammilAIX)
