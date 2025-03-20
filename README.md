# Credit Card Fraud Detection System

## Project Overview
This project implements a machine learning model to detect fraudulent credit card transactions. The system uses advanced feature engineering and a Random Forest classifier to identify potentially fraudulent activities with high accuracy.

## Task Objectives
- Develop a robust fraud detection system using machine learning
- Implement effective feature engineering to improve model performance
- Handle class imbalance in fraud detection data
- Evaluate model performance using multiple metrics
- Create a system that can be easily implemented in production environments

## Technical Approach
The project utilizes:
- Random Forest classification algorithm
- SMOTE (Synthetic Minority Over-sampling Technique) for handling class imbalance
- Feature engineering to create meaningful predictors
- Standardization of numerical features
- Comprehensive evaluation metrics

## Requirements
- Python 3.7+
- pandas
- scikit-learn
- imbalanced-learn
- numpy

## Installation
1. Clone the repository:
```
git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection
```

2. Install the required dependencies:
```
pip install -r requirements.txt
```

## Dataset
The project uses the "creditcard.csv" dataset, which contains anonymized credit card transactions. Each transaction is labeled as fraudulent (1) or legitimate (0).

## Steps to Run the Project
1. Place the "creditcard.csv" file in the project directory or update the file path in the code.

2. Run the main script:
```
python fraud_detection.py
```

3. Review the output metrics to evaluate model performance:
   - Accuracy
   - Precision
   - Recall
   - F1 Score
   - ROC-AUC Score

## Code Structure
- `fraud_detection.py`: Main script containing the full implementation
- `requirements.txt`: List of required Python packages
- `README.md`: This file

## Feature Engineering
The project enhances the original dataset with several engineered features:
- Transaction frequency
- Hour of transaction
- Location mismatch simulation
- Spending deviation from average

## Model Training and Evaluation
The implementation follows these steps:
1. Load and preprocess the data
2. Apply feature engineering
3. Standardize numerical features
4. Apply SMOTE to handle class imbalance
5. Split data into training and testing sets
6. Train a Random Forest classifier
7. Evaluate using multiple metrics

