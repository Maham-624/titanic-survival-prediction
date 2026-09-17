# Titanic Survival Prediction | Machine Learning

## Project Overview

This project develops an end-to-end machine learning workflow to predict passenger survival in the Kaggle Titanic competition.

The project focuses on data exploration, preprocessing, feature engineering, cross-validation, model comparison, hyperparameter tuning, and evaluation on the Kaggle leaderboard.

## Objectives

- Explore patterns associated with passenger survival.
- Clean and preprocess the Titanic dataset.
- Engineer meaningful features from passenger information.
- Compare multiple classification algorithms.
- Use cross-validation for reliable model evaluation.
- Tune promising models using hyperparameter optimization.
- Generate predictions for the Kaggle competition.

## Dataset

The project uses the official Titanic competition dataset provided by Kaggle.

- Training observations: 891
- Test observations: 418
- Target variable: `Survived`

## Project Workflow

1. Data loading and inspection
2. Exploratory Data Analysis (EDA)
3. Missing-value handling
4. Feature engineering
5. Preprocessing pipeline
6. Model comparison using cross-validation
7. Hyperparameter tuning
8. Kaggle submission generation
9. Leaderboard evaluation

## Feature Engineering

Several features were created or extracted to improve the representation of passenger information, including:

- `FamilySize`
- `IsAlone`
- `CabinKnown`
- `Title`
- `Deck`
- `FamilyCategory`

Additional features such as `FarePerPerson` and `AgeGroup` were experimentally evaluated.

## Machine Learning Models

Multiple classification algorithms were investigated, including:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- Gradient Boosting

Cross-validation was used to compare model performance before generating Kaggle submissions.

## Kaggle Submission Results

| Submission | Model | Cross-Validation Accuracy | Kaggle Score |
|---|---|---:|---:|
| Submission 1 | Tuned XGBoost | 0.8462 | **0.77033** |
| Submission 2 | Tuned Gradient Boosting | 0.8451 | 0.76076 |

The tuned XGBoost submission achieved the higher Kaggle leaderboard score of **0.77033**.

The experiments also demonstrate an important machine learning lesson: a similar or slightly improved validation strategy does not necessarily produce a higher unseen leaderboard score.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Machine Learning
- Feature Engineering
- Cross-Validation
- Hyperparameter Tuning

## Project Notebook

The complete analysis, feature engineering, model development, evaluation, and Kaggle submission experiments are available in the Jupyter notebook included in this repository.

## Future Improvements

Future work may investigate additional relationship-based features such as family groups and ticket-sharing patterns, alternative validation strategies, and further ensemble approaches.

## Author

**Maham-624**  
Mathematics | Data Analytics | Machine Learning | Cryptography
