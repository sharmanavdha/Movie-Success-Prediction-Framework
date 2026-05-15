# Predictive Movie Success Model
This project uses Machine Learning techniques to predict whether a movie will be a 
**Success** or **Failure** based on various movie-related features such as genres, languages, release date, trend scores, and other metadata.

---

## Project Overview
The notebook performs:

- Data preprocessing
- Feature engineering
- Data scaling
- Handling imbalanced datasets using SMOTE
- Model training and evaluation
- Hyperparameter tuning
- Feature importance analysis

The goal is to build a predictive classification model for movie success prediction.

-----------

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Imbalanced-learn (SMOTE)
- Matplotlib
- Seaborn

-----------

## Machine Learning Models Used
- Random Forest Classifier
- Logistic Regression
- XGBoost Classifier

-----------

## Features Engineering
The following transformations and features were created:
- Release Year
- Release Month
- Release Quarter
- Genre Encoding
- Language Encoding
- Genre Trend Score
-----------

## Dataset Processing

### Data Cleaning
- Converted release dates into datetime format
- Removed missing values
- Encoded categorical features

### Data Balancing
The dataset was highly imbalanced, so **SMOTE** was used to oversample the minority class.
-----------

## Model Evaluation Metrics

The models were evaluated using:

- Accuracy Score
- F1 Score
- ROC-AUC Score
- Classification Report
- Confusion Matrix
-----------

## Feature Importance Analysis

Feature importance visualization was generated to identify the most influential factors affecting movie success prediction.
-----------

## Project Structure

```text
Predictive Model.ipynb
README.md
dataset.xlsx
```

---

## Installation

Install required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost imbalanced-learn openpyxl
```

---

## Run the Project

Open Jupyter Notebook:

```bash
jupyter notebook
```

Then run:

```text
Predictive Model.ipynb
```

---

## Future Improvements
- Add Deep Learning models
- Improve feature engineering
- Deploy model as a web application
- Add real-time prediction interface
- Improve class imbalance handling

---

## Author
Developed as a Machine Learning predictive analytics project.

---

## License
This project is open-source and available under the MIT License.