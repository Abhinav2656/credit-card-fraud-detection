# Credit Card Fraud Detection

## Task Objectives
This project is designed to develop a classification model that efficiently detects fraudulent credit card transactions. The key objectives include:
- **Feature Engineering:** Creating meaningful features such as transaction frequency, simulated location mismatch, and spending deviation to capture unusual transaction patterns.
- **Handling Class Imbalance:** Employing SMOTE (Synthetic Minority Oversampling Technique) to balance the dataset, ensuring that the minority class (fraudulent transactions) is well-represented.
- **Model Development & Evaluation:** Training a Random Forest classifier and evaluating its performance using multiple metrics (Accuracy, Precision, Recall, F1-Score, and ROC-AUC) to minimize false positives and achieve high accuracy.

## Project Structure
- **creditcard_fraud.py / creditcard_fraud.ipynb:** Main file containing the complete implementation.
- **requirements.txt:** Lists the required Python libraries.
- **README.md:** This file, describing the project and instructions to run it.

## Steps to Run the Project

### 1. Clone the Repository
Open your terminal and run:
```bash
git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection```


### 2. Install Dependencies

Ensure you have Python installed. Then, install the necessary packages:
```bash
pip install -r requirements.txt
```
