# Flight Delay Prediction

This project uses machine learning to predict flight delays based on historical flight data.

## Models Implemented
- Logistic Regression
- Random Forest
- Decision Tree

## Dataset
The dataset contains flight information including:
- Month, day of month, day of week
- Carrier information
- Origin and destination airports
- Departure time and delays
- Target variable: DEP_DEL15 (1 if delayed 15+ minutes, 0 otherwise)

## Project Structure
- `1_logistic_regression.ipynb`: Implementation using logistic regression
- `2_random_forest.ipynb`: Implementation using random forest
- `3_decision_tree.ipynb`: Implementation using decision tree
- `data/`: Contains the flight delay dataset