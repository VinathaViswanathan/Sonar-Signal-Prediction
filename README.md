# Sonar-Signal-Prediction
This project aims to classify sonar signals as either rocks or mines using a Logistic Regression model. The dataset contains energy readings of sonar signals bounced off different objects. Logistic Regression is chosen due to its effectiveness in binary classification problems.

## Project Workflow:

### Data Collection: 
Load the Sonar dataset containing 60 numeric features and binary labels ('R' for Rock, 'M' for Mine).

### Data Pre-processing: 
Encode labels, scale features if necessary, and perform basic exploratory data analysis to understand the distribution.

### Train-Test Split: 
Split the data into training and testing sets (e.g., 80/20) to evaluate model performance.

### Model Training - Logistic Regression: 
Train a logistic regression model on the training data and evaluate using accuracy, precision, recall, and F1-score.
