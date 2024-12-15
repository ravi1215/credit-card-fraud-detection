# Credit Card Fraud Detection

## Overview

This project is a **Credit Card Fraud Detection** system built using machine learning (ML). It is designed to detect fraudulent transactions based on various features available in a credit card transaction dataset. The model is trained using a dataset of credit card transactions, and the goal is to identify whether a transaction is fraudulent or legitimate.

### Machine Learning Models Used:
- **Logistic Regression**: A statistical model used to predict the probability of a transaction being fraudulent or legitimate.
- **Decision Tree**: A classification algorithm that splits data based on feature values to predict the outcome (fraudulent or legitimate).

## Project Files

- `creditcard_fraud.ipynb`: Jupyter notebook containing the machine learning model and code to train and evaluate the fraud detection models (Logistic Regression and Decision Tree).
- `credit_card_model.pkl`: Trained machine learning model (saved in pickle format) for later use.
- `.gitignore`: This file ensures that large and unnecessary files (like `.ipynb_checkpoints` and model files) are not tracked by Git.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/ravi1215/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
   ```
Install the required dependencies:

It is recommended to use a virtual environment. You can install the required dependencies by running:
```bash
pip install -r requirements.txt
```

Dataset link - https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
