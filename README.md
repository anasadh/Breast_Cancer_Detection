# Breast Cancer Detection using Logistice Regression 
Breast Cancer Detection using using Logistice Regression

## Overview
This project focuses on utilizing logistic regression to create a model for the detection of breast cancer, specifically classifying tumors as either benign or malignant. The dataset used is the Breast Cancer Wisconsin (Diagnostic) dataset, obtained from the UCI ML Breast Cancer Wisconsin (Diagnostic) datasets.

## Dataset
The dataset comprises 569 instances with 30 features each. The features include various metrics such as mean radius, mean texture, mean perimeter, and so on, computed from digitized images of fine needle aspirates of breast masses. The class labels are binary, with '0' representing malignant tumors and '1' representing benign tumors.

## Code Structure

### Step 1: Loading and Exploring the Dataset
Import necessary libraries.
Load the breast cancer dataset.
Explore and understand the dataset.
Convert the dataset into a Pandas DataFrame for better analysis.
### Step 2: Train and Test Split
Split the dataset into training and testing sets.
Ensure the distribution of classes is maintained during the split.
Optionally, perform data scaling for better model performance.
### Step 3: Logistic Regression
Initialize a Logistic Regression model.
Scale the training data using StandardScaler.
Train the logistic regression model on the scaled data.
### Step 4: Evaluation of the Model
Use the trained model to make predictions on both training and testing datasets.
Evaluate the accuracy of the model using metrics such as accuracy_score.
### Step 5: Detecting Breast Cancer
Provide input data for prediction.
Transform the input data and make predictions using the trained model.
Interpret the predictions and classify breast cancer as either benign or malignant.

## How to Use
Install dependencies: 
```python
pip install numpy scikit-learn pandas.
```

Run the provided Jupyter Notebook or Python script.
Explore the results, model accuracy, and make predictions on new data.

## Contributor
Anamika Sadh

## Acknowledgments
Dataset source: UCI ML Breast Cancer Wisconsin (Diagnostic) datasets.
## License
This project is licensed under the MIT License.


