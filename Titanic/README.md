# Titanic - Machine Learning from Disaster

This repository contains my solution for the Kaggle competition [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic).

## Overview
The Titanic competition is a binary classification problem where we predict whether a passenger survived the Titanic disaster based on features such as age, class, gender, and ticket fare.

## Dataset
- **Train dataset:** `train.csv` (used for model training)
- **Test dataset:** `test.csv` (used for making predictions)
- **Submission file:** `submission.csv` (contains the final predictions to submit)

## Installation
Ensure you have the necessary dependencies installed:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Files
- `titanic_solution.ipynb` - Jupyter Notebook containing the solution.
- `titanic_solution.py` - Python script version of the solution.
- `data/` - Directory to store dataset files.
- `models/` - Directory to save trained models.
- `submission.csv` - Final predictions for Kaggle submission.

## Model & Approach
The model used for this solution includes:
- Data preprocessing (handling missing values, feature engineering, encoding categorical variables)
- Machine learning models such as Logistic Regression, Random Forest, and XGBoost
- Hyperparameter tuning using GridSearchCV
- Model evaluation using accuracy, precision, recall, and F1-score

## Results
Final accuracy on training data: **77.7%**  

## Author
Sri Sai Durga Katreddi

## License
This project is licensed under the MIT License.
