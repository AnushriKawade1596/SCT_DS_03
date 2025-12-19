# SCT_DS_03 — Decision Tree Classifier (Bank Marketing Dataset)

## Objective
The objective of this project is to build a Decision Tree classifier to predict whether a customer will purchase a product or service based on demographic and behavioral data.

## Dataset
- **Source:** UCI Machine Learning Repository  
- **Dataset Name:** Bank Marketing Dataset  
- **File Used:** bank.csv  
- **Target Variable:** `y`  
  - `yes` → customer subscribed  
  - `no` → customer did not subscribe  

## Project Workflow
1. Loaded and inspected the dataset
2. Identified features and target variable
3. Encoded categorical variables using Label Encoding
4. Split the data into training and testing sets
5. Built a Decision Tree Classifier
6. Evaluated the model using:
   - Accuracy
   - Confusion Matrix
   - Classification Report
7. Visualized and saved the trained Decision Tree

## Results
- The model achieved an accuracy of **89%**
- The model performs very well in predicting non-subscribers
- Prediction of subscribers is affected by class imbalance
- The decision tree visualization provides interpretability of model decisions

## Repository Structure

