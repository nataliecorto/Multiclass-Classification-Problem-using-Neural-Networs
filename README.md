# Multiclass-Classification-Problem-using-Neural-Networs
Multiclass Classification of Chronic Heart Disease

# Dataset Information 
The Heart Disease dataset from the UCI Machine Learning Repository was used as the datasource for this project.

Specifically, using one of the processed datasets from Cleveland, which has 14 attributes (most important ones used in other scientific works) from the total 76 features.

The dataset comprises 303 observations, 13 features, and 1 target attribute. The 13 features include the results of non-invasive diagnostic tests along with other relevant patient information. The target variable includes the result of the invasive coronary angiogram which represents the presence or absence of coronary artery disease in the patient with 0 representing the absence of CHD and labels 1-4 representing the presence of CHD. 

Full details of attributes can be found here: 

Link: https://archive.ics.uci.edu/ml/datasets/heart+disease

# Objectives

Develop a multi-class Neural Network (NN) classifier to predict the CHD outcome (0-4). Create, train, and test a neural network architecture using Keras.

(a) the softmax activation function for multiclass outcomes
(b) convert a single multi-class outcome column to multiple outcome column using one-hot encoding
(c) evaluating multi-class predictions using classification_report
Note the dataset is not a text classification dataset, so there is no need to create a CNN architecture. A simple neural network architecture will be enough.

# Order to read and load files : 
## Step 1 
- download the Heart Disease files from the UCI Machine Learning Repository
  - chd_processed_cleveland.csv
  
## Step 2 
- Load and read through the .ipynb file with code and explanation of steps 
  - multiClassNN.ipynb
