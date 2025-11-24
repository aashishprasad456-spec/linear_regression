# Insurance Charges Prediction Model
Insurance Charges Prediction Using Linear Regression

Overview
This project builds a machine learning model that predicts medical insurance charges based on demographic and lifestyle factors such as age, sex, BMI, number of children, and smoking status. The dataset is cleaned, encoded, split into training/testing sets, and finally used to train a Linear Regression model. The trained model is saved as a `.pkl` file for future use.

Features

* Data preprocessing (encoding + cleaning)
* Label encoding for categorical variables
* Linear Regression model training
* Evaluation using R² score
* Train-test split for model validation
* Saving trained model with Pickle
* Simple and beginner‑friendly workflow

Technologies / Tools Used

* Python 3
* NumPy
* Pandas
* Matplotlib
* Scikit‑Learn (LabelEncoder, LinearRegression, train_test_split)
* Pickle for saving the model

Steps to Install & Run the Project

Install Dependencies
Run the following command:
pip install numpy pandas scikit-learn matplotlib

Add the Dataset

Run the Project:
python main.py

Output
* Displays model accuracy (R² score)
* Saves the trained model as **model.pkl**

Instructions for Testing

1. Ensure the dataset is correctly formatted and available.
2. Modify input feature values in a separate inference script (optional).
3. Load the model using Pickle
4. Provide a test input (as a list or DataFrame row) to `model.predict()`.

