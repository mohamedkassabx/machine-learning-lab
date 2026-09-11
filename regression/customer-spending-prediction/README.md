# Customer Spending Prediction

A small Machine Learning project focused on predicting a customer's yearly spending using Lasso Regression.

This project is part of my Machine Learning learning journey and was created to practice the basic Regression workflow using a real-world customer dataset.

## Objective

The goal of this project is to build a regression model that predicts the `Yearly Amount Spent` by a customer based on their available numerical features.

## Dataset

The dataset contains information about e-commerce customers and their yearly spending.

The target variable is:

- `Yearly Amount Spent`

The dataset also contains customer-related features such as:

- Average Session Length
- Time on App
- Time on Website
- Length of Membership

Non-predictive or identifying columns such as `Email`, `Address`, and `Avatar` were excluded from the features.

## Workflow

### 1. Load Dataset

Loaded the dataset using Pandas and inspected its structure and contents.

### 2. Features and Target

Separated the dataset into:

- Features (`X`)
- Target (`y`)

The target variable is `Yearly Amount Spent`.

The following columns were removed from the features:

- `Email`
- `Address`
- `Avatar`
- `Yearly Amount Spent`

### 3. Train-Test Split

Split the dataset into training and testing sets using `train_test_split`.

The training set contains 70% of the data, while the remaining 30% is used for testing.

### 4. Lasso Regression Model

Used Lasso Regression as the Machine Learning model.

The model was initialized with:

- `alpha=1.0`

### 5. Model Training

Trained the Lasso Regression model using the training data.

### 6. Predictions

Used the trained model to predict the yearly spending of customers in the test dataset.

### 7. Model Evaluation

Evaluated the model using Mean Squared Error (MSE).

## Machine Learning Concepts Practiced

- Regression
- Train-Test Split
- Feature Selection
- Lasso Regression
- Model Training
- Predictions
- Model Evaluation
- Mean Squared Error

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Requirements

The required Python packages are listed in `requirements.txt`.

## How to Run

### 1. Clone the Repository

```bash
git clone <repository-url>
cd customer-spending-prediction
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

### 3. Activate the Virtual Environment

On Windows:

```bash
.venv\Scripts\activate
```

On macOS/Linux:

```bash
source .venv/bin/activate
```

### 4. Install Requirements

```bash
pip install -r requirements.txt
```

### 5. Run the Notebook

Start Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
customer-spending-prediction.ipynb
```

Run the cells in order.

## Project Structure

```text
customer-spending-prediction/
│
├── dataset/
│   └── Ecommerce Customers.csv
│
├── customer-spending-prediction.ipynb
├── requirements.txt
└── README.md
```

## Conclusion

This project helped me practice the basic Machine Learning workflow for Regression, from selecting the relevant features and splitting the data to training a Lasso Regression model, making predictions, and evaluating its performance.

It is one of the small practical projects I am building while learning Machine Learning.