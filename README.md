# Credit Card Default Prediction — Logistic Regression

Two logistic regression models predicting whether a client will default on their credit card payment.

## Dataset
UCI "Default of Credit Card Clients" dataset — 30,000 clients, 25 variables.

## Approach
- Model 1: predicts default using payment status, bill amount, and credit limit.
- Model 2: adds an interaction term (bill amount × credit limit) plus sex, age, and education.
- Compared both models using AIC to assess which better fits the data.

## Result
Both models achieve **~81% accuracy**. Model 2 shows a better fit (lower AIC: ~28,188 vs. ~28,294), indicating the added interaction term and demographic variables improve the model.

## Files
- `Credit_Card_Default_Logistic_Regression.Rmd` — full analysis in R Markdown
