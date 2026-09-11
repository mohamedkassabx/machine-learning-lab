# Car Price Prediction

A small Machine Learning project focused on predicting car prices using Lasso Regression.

This project is part of my Machine Learning learning journey and was created to practice the fundamentals of Regression using a real-world dataset.

## Objective

The goal of this project is to build a regression model that predicts the price of a car based on its available features.

## Dataset

The dataset contains information about cars and their prices, including categorical and numerical features.

The target variable is:

- `Price`

## Workflow

### 1. Load Dataset

Loaded the dataset and inspected its structure and contents.

### 2. Features and Target

Separated the dataset into:

- Features (`X`)
- Target (`y`)

The target variable is the car `Price`.

### 3. Train-Test Split

Split the dataset into training and testing sets using `train_test_split`.

### 4. One-Hot Encoding

Converted categorical features into numerical features using `OneHotEncoder`.

Used `handle_unknown="ignore"` to handle categories that may appear in the test data but were not present during training.

### 5. Lasso Regression Model

Used Lasso Regression as the machine learning model.

### 6. Model Training

Trained the Lasso Regression model using the training data.

### 7. Predictions

Used the trained model to predict car prices for the test dataset.

### 8. Model Evaluation

Evaluated the model using Mean Squared Error (MSE).

### 9. Manual Prediction

Tested the trained model with manually provided car information to generate a price prediction.

## Machine Learning Concepts Practiced

- Regression
- Train-Test Split
- Categorical Feature Encoding
- One-Hot Encoding
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
cd car-price-prediction
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
car_price_prediction.ipynb
```

Run the cells in order.

## Project Structure

```text
car-price-prediction/
│
├── dataset/
│   └── Car_Price_Prediction.csv
│
├── car-price-prediction.ipynb
├── requirements.txt
└── README.md
```

## Conclusion

This project helped me practice the basic Machine Learning workflow for Regression, from preparing the data and encoding categorical features to training a model, making predictions, and evaluating its performance.

It is one of the small practical projects I am building while learning Machine Learning.