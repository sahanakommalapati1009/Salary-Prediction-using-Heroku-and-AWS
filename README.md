# Salary Prediction Using Heroku and AWS EC2
This repository contains a Flask-based web application for predicting employee salaries based on features like experience, test scores, and interview scores. The application leverages machine learning and provides deployment instructions for both Heroku and AWS EC2.

## Features
### 1. Dataset:
* The dataset includes employee details such as years of experience, test scores, and interview scores.
* Salary is the target variable to predict.
### 2. Model:
* A Linear Regression model is trained using the dataset to predict employee salaries.
* The trained model is serialized using pickle and utilized by the Flask application.
### 3. Web Application:
* Built using Flask, the web app provides a simple user interface for inputting employee details and receiving salary predictions.
### 3. Deployment Options:
* The application can be deployed on Heroku for ease of access.
* It can also be hosted on an AWS EC2 instance for greater customization and control.

## Technologies Used
* Flask: For building the web application.
* Heroku: For easy application deployment.
* AWS EC2: For hosting the application in a cloud environment.
* Linear Regression: For salary prediction.
* Python Libraries:
  - pandas, numpy: For data processing.
  - scikit-learn: For machine learning.

## Usage Instructions
### 1. Ensure Prerequisites Are Installed:
* Install Python (version 3.9 or above recommended).
* Set up Heroku CLI and an AWS account with an EC2 instance configured.
### 2. Install Required Dependencies: 
* Run the following command in your terminal to install the necessary Python libraries:
  - pip install -r requirements.txt
### 3. Prepare and Train the Model:
* If you wish to retrain the model, execute the following script to preprocess the data and train the model:
  - python model.py
### 4. Run the Application Locally:
* Start the Flask application:
  - python app.py
* Open a browser and go to http://127.0.0.1:5000/ to test the application.
### 5. Deploy on Heroku:
* Create a Heroku application
* URL:
### 6. Set Up on AWS EC2:
* Launch an EC2 instance with a public IP.
* Install dependencies and upload your application files to the instance.
* Start the Flask application on the EC2 instance and ensure the instance's security group allows HTTP traffic on port 5000
### 7. Predict Salaries:
* Use the deployed application to input experience, test score, and interview score, and the app will predict the employee’s salary.
### 8. Access Application:
* For Heroku: 
* For AWS EC2:

