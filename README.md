# Two-Wheeler-Loan-Risk-Assessment
Loan Risk Classification Model
This repository contains a machine learning model for classifying loan applications into two categories: APPROVED and DECLINED. The project includes code for data preprocessing, model training, evaluation, and making predictions.

Table of Contents
Project Overview
Data
Dependencies
Usage
Model Performance
License
Contact
Project Overview
The goal of this project is to build a predictive model that can automate the classification of loan applications. The project employs a Random Forest Classifier, integrated with preprocessing steps to handle missing values, encode categorical features, and scale numerical data.

The model is evaluated based on its accuracy, precision, recall, and F1-score.

Data
The project uses two CSV files:

Assignment_Train.csv: Training dataset with labeled loan application data.
Assignment_Test.csv: Test dataset used for making predictions.
Data columns include:

Personal details
Loan-related features
Application information
Note: Ensure the datasets are available in the root directory of the project.

Dependencies
The project requires the following Python libraries:

pandas
numpy
scikit-learn
To install the required dependencies, use the following command:

bash
Copy code
pip install pandas numpy scikit-learn
Usage
Clone the Repository

bash
Copy code
git clone https://github.com/your-username/loan-risk-classification.git
cd loan-risk-classification
Prepare the Data

Ensure that Assignment_Train.csv and Assignment_Test.csv are placed in the root directory of the project.

Run the Model

Execute the script loan_classification.py to preprocess the data, train the model, evaluate its performance, and generate predictions.

bash
Copy code
python loan_classification.py
This script will:

Load and preprocess the data.
Train a Random Forest Classifier.
Evaluate the model on the training data.
Make predictions on the test data.
Save the predictions to predictions.csv.
Check the Results

After running the script, check loan_predictions.csv for test data predictions and model_performance.txt for evaluation metrics.

Model Performance
The Random Forest Classifier achieved the following metrics on the training dataset:

Accuracy: 86.2%
Precision:
APPROVED: 0.94
DECLINED: 0.75
Recall:
APPROVED: 0.85
DECLINED: 0.89
F1-Score:
APPROVED: 0.89
DECLINED: 0.81
The model demonstrates strong performance in distinguishing between approved and declined loans, with a balanced approach to precision and recall.


Contact
For any questions or issues, please contact:

Name: Atul Kumar
Email: atul70911@gmail.com
