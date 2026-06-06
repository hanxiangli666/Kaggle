# Kaggle

Machine-learning practice repository focused on the Titanic competition workflow: problem framing, data cleaning, feature engineering, model comparison, and submission generation.

## Current Project: Titanic Survival Prediction

The main notebook is `titanic_simplified.ipynb`.

It follows a practical data-science process:

1. Define the prediction problem.
2. Inspect train/test data.
3. Identify missing values and data types.
4. Clean `Age`, `Fare`, `Embarked`, and related fields.
5. Engineer features such as family size, alone status, title, age bins, and fare bins.
6. Encode categorical variables.
7. Compare model-ready feature sets.
8. Generate Kaggle submission CSV files.

## Repository Contents

```text
titanic_simplified.ipynb       Main cleaned notebook
fork-of-the-first-shot.ipynb   Earlier experiment
train.csv                      Titanic training data
test.csv                       Titanic test data
submission.csv                 Submission output
submission2.csv                Alternative submission output
convert_cn.py                  Notebook/text conversion helper
best_score.py                  Placeholder for score tracking
```

## Skills Demonstrated

- Data cleaning and missing-value handling.
- Exploratory data analysis.
- Feature engineering for tabular ML.
- Categorical encoding.
- Train/test separation and submission workflow.
- Translating and annotating a public Kaggle learning framework into a personal study notebook.

## Suggested Next Step

To make this repository stronger for applications and recruiting:

- Add model comparison tables.
- Record the exact Kaggle public score.
- Keep one clean final notebook and one experiment notebook.
- Add a short section explaining which feature decisions improved performance.

## Run

Open the notebook in Jupyter, VS Code, or Kaggle Notebooks:

```powershell
jupyter notebook titanic_simplified.ipynb
```

## Position In My Portfolio

This repository is supporting evidence for ML fundamentals. It is not positioned as a production product; it shows tabular data-science practice and feature-engineering discipline.
