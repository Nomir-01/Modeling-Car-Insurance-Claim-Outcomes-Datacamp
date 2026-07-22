# Modeling Car Insurance Claim Outcomes

A predictive-modeling exercise that evaluates which individual customer feature is most informative for car-insurance claim outcomes. The notebook handles missing values, fits a series of logistic regression models, compares their accuracy, and reports the strongest single feature.

## Workflow

1. Inspect the insurance dataset and target variable.
2. Handle missing values in the modeling features.
3. Fit a logistic regression model for each candidate feature.
4. Calculate and compare classification accuracy.
5. Return the best-performing feature and its score.

## Tools

- Python
- pandas and NumPy
- statsmodels
- Jupyter Notebook

## Repository contents

- `notebook.ipynb` — preprocessing, modeling, and model comparison
- `car_insurance.csv` — insurance customer data
- `car.jpg` — project cover image
- `requirements.txt` — Python dependencies

## Run locally

```bash
python -m venv .venv
python -m pip install -r requirements.txt
jupyter lab notebook.ipynb
```

## Project context

This is a personal learning project completed as guided DataCamp coursework. It demonstrates missing-data handling, binary classification with logistic regression, and systematic feature comparison.
