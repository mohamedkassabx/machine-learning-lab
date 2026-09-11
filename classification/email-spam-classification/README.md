# Email Spam Classification

A machine learning project for classifying emails as **Spam** or **Not Spam** using the **Multinomial Naive Bayes** algorithm.

## Dataset

The project uses the **Email Spam Classification Dataset** from Kaggle.

- 5,172 emails
- 3,002 columns
- `Email No.` → Email identifier
- `Prediction` → Target variable
  - `0` → Not Spam
  - `1` → Spam

The dataset is not included in this repository.

Kaggle Dataset:
https://www.kaggle.com/datasets/balaka18/email-spam-classification-dataset-csv

## Technologies

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Workflow

1. Load the dataset
2. Perform Exploratory Data Analysis (EDA)
3. Check missing values and statistics
4. Analyze the target distribution
5. Separate features and target
6. Remove the email identifier
7. Split the data using a stratified train/test split
8. Train a Multinomial Naive Bayes model
9. Generate predictions and prediction probabilities
10. Evaluate the model using Precision, Recall, F1-score, and Confusion Matrix

## Model

**Multinomial Naive Bayes**

The model is trained using `MultinomialNB` with `alpha=1.0`.

## Model Evaluation

The project evaluates the model using:

- Precision
- Recall
- F1-score
- Confusion Matrix

The notebook also visualizes the confusion matrix and the model's evaluation metrics.

## Project Structure

email-spam-classification/
├── email-spam-classification.ipynb
├── README.md
├── requirements.txt

## What I Learned

- Exploratory Data Analysis
- Feature and target separation
- Stratified train/test splitting
- Multinomial Naive Bayes
- Making predictions and probabilities
- Precision, Recall, and F1-score
- Confusion Matrix
- Basic machine learning classification workflow

## Future Improvements

- Cross-validation
- Compare different classification models
- Feature selection
- Hyperparameter tuning
- Error analysis