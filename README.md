# credit-risk-prediction
Credit Risk Prediction using Machine Learning – ML600 assignment comparing classification models, PCA and hyperparameter tuning.
# Credit Risk Prediction Using Machine Learning

## Project Overview

This project explores the use of supervised machine learning to predict loan default risk using historical customer and loan data.

The project was completed as part of the ML600 – Machine Learning assignment.

## Dataset

The project uses the Credit Risk Dataset obtained from Kaggle.

- **Source:** [Credit Risk Dataset – Kaggle] = (https://www.kaggle.com/datasets/laotse/credit-risk-dataset)
- **Records:** 32,581 customer records
- **Target variable:** `loan_status`
- **Problem type:** Binary classification

The dataset is not included in this repository. Please download it from the original Kaggle source before running the notebook.

## Technologies and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Techniques

- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Missing value imputation
- Binary, ordinal and one-hot encoding
- Min-Max scaling
- Logistic Regression
- K-Nearest Neighbours (KNN)
- Decision Tree Classification
- Principal Component Analysis (PCA)
- GridSearchCV hyperparameter optimisation

## Model Results

Three classification models were evaluated before and after PCA.

The original-feature Decision Tree achieved 89.18% accuracy.

After hyperparameter optimisation using GridSearchCV, the Decision Tree achieved 93.36% accuracy.

PCA reduced the original 19 features to 8 principal components while retaining 93.94% of the variance.

## Project Files

- `credit_risk_prediction.ipynb` – Main Jupyter Notebook containing the analysis and machine learning implementation.
- `credit_risk_presentation.pdf` – Project presentation covering the methodology, findings and conclusions.

## How to Run

1. Download the dataset from the Kaggle link above.
2. Place `credit_risk_dataset.csv` in the same directory as the notebook.
3. Install the required Python libraries.
4. Open the notebook using Jupyter Notebook or JupyterLab.
5. Run the notebook cells.

## Author

Mohamed Ahmed

Machine Learning – ML600
