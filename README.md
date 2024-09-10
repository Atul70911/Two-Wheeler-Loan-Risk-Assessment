# Two-Wheeler-Loan-Risk-Assessment
This repository provides a machine learning solution for classifying loan applications into APPROVED or DECLINED categories. The script performs data preprocessing, model training, evaluation, and prediction using a Random Forest Classifier.

Overview
The loan_classification.py script includes the following steps:

Data Loading: Reads training and test datasets.
Preprocessing: Cleans and prepares the data for modeling.
Model Training: Uses a Random Forest Classifier to train on the training dataset.
Evaluation: Assesses model performance on the training set.
Prediction: Generates predictions on the test dataset and saves them to a CSV file.
File Structure
loan_classification.py: The main script for data preprocessing, model training, evaluation, and prediction.
Assignment_Train.csv: Training data (to be provided).
Assignment_Test.csv: Test data (to be provided).
predictions.csv: Contains the UID and predicted status for the test dataset.
Prerequisites
Ensure you have the following Python packages installed:

pandas
numpy
scikit-learn
You can install the required packages using pip:


pip install pandas numpy scikit-learn
Usage
Clone the Repository


git clone https://github.com/your-username/loan-risk-classification.git
cd loan-risk-classification
Prepare the Data

Place Assignment_Train.csv and Assignment_Test.csv in the root directory of the project.

Run the Script

Execute the script to preprocess data, train the model, evaluate it, and generate predictions:


python loan_classification.py
The script will output:

predictions.csv: Contains predictions for the test dataset.
Model performance metrics printed to the console.
Model Performance
The Random Forest Classifier achieves the following performance metrics on the training data:

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
Contact
For any questions or issues, please contact:

Name: Atul Kumar
Email: atul70911@gmail.com
