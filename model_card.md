# Model Card

## Model Description

**Input:** Gold OHLCV daily log returns

**Output:** A binary classification of the 1-day forward return sign 

**Model Architecture:** Logistic Regression

## Performance

see accuracy score graph

## Limitations

The model is linear in nature and does not incorporate any non-linearity or conditionality into it's learning

## Trade-offs

Heteroscedasticity will degrade the model performance over time.
The train-test split should be upgraded to an expanding window walk-forward with weekly training