# Gender Prediction

A machine learning project for predicting gender using the **Random Forest Classifier**.

## Dataset

The project uses the `gender_classification_v7.csv` dataset.

The target column is:

- `gender` → Target variable

All other columns are used as features.

## Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Workflow

1. Load the dataset
2. Explore the data
3. Check missing values and statistics
4. Separate features and target
5. Split the data into training and testing sets
6. Train a Random Forest Classifier
7. Generate predictions and prediction probabilities
8. Evaluate the model using Classification Report and Confusion Matrix
9. Review sample predictions

## Model

**Random Forest Classifier**

- `n_estimators=100`
- `max_depth=2`
- `criterion='gini'`
- `random_state=33`

## Model Evaluation

The model is evaluated using:

- Precision
- Recall
- F1-score
- Confusion Matrix

The confusion matrix is also visualized using Seaborn.

## Project Structure

```text
gender-prediction-classification/
│
├── dataset/
│   └── gender_classification_v7.csv
│
├── gender-prediction-classification.ipynb
├── requirements.txt
└── README.md
```

## What I Learned

- Exploratory Data Analysis
- Feature and target separation
- Train/test splitting
- Random Forest Classification
- Classification metrics
- Confusion Matrix
- Making predictions and prediction probabilities

## Future Improvements

- Use stratified train/test splitting
- Add a random state to the train/test split
- Compare different classification models
- Hyperparameter tuning
- Cross-validation