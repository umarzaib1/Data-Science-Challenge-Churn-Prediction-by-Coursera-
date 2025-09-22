# Data-Science-Challenge-Churn-Prediction-by-Coursera-
Churn Prediction Challenge
This project tackles the churn prediction problem for a video streaming service. The goal is to build a machine learning model that can predict which existing subscribers are most likely to cancel their subscription in the upcoming month.

Dataset
The dataset consists of two files: train.csv and test.csv.

train.csv: Contains 70% of the sample data with the target variable Churn, indicating whether a subscriber churned (1) or not (0).
test.csv: Contains the remaining 30% of the sample data without the Churn column. The task is to predict the churn probability for these subscribers.
The datasets include various features related to customer account information, subscription details, viewing habits, and support interactions. A detailed description of each column is provided in the data_descriptions.csv file.

Project Structure
The notebook is structured as follows:

Introduction: Provides an overview of the problem and the dataset.
Understanding the Datasets: Explains the train/test split and describes the features.
Import Python Modules: Imports necessary libraries for data manipulation, machine learning, and visualization.
Load the Data: Loads the train.csv and test.csv files into pandas DataFrames.
Explore, Clean, Validate, and Visualize the Data (optional): This section is for optional data exploration and preprocessing steps.
Data Preparation: Prepares the data for modeling, including handling categorical features using one-hot encoding.
Model Training: Trains a Logistic Regression model on the training data.
Make predictions (required): Generates churn probability predictions for the test data using the trained model.
Final Tests: Includes assertion tests to ensure the prediction submission is in the correct format.
SUBMIT YOUR WORK!: Instructions on how to submit the predictions.
Model
A Logistic Regression model is used for churn prediction. The model is trained on the preprocessed training data (X_train, y_train) and used to predict churn probabilities on the preprocessed test data (X_test).

Submission
The final submission requires a CSV file named prediction_submission.csv with two columns:

CustomerID: The unique identifier for each customer.
predicted_probability: The predicted probability of churn for each customer.
The prediction_df DataFrame generated in the notebook should have exactly 104,480 rows and the specified columns.

How to Run the Notebook
Ensure you have the necessary datasets (train.csv, test.csv, data_descriptions.csv) in the same directory as the notebook.
Run each code cell sequentially.
Modify the "Explore, Clean, Validate, and Visualize the Data" and "Make predictions" sections to experiment with different models and techniques to improve prediction accuracy.
Run the final test cells to verify the submission format.
Generate the prediction_submission.csv file.
Submit the prediction_submission.csv file for evaluation. 
