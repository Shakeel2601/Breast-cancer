# Breast-cancer-detection
Implement an ml model for the breast cancer dataset using logistic regression.
The dataset has 31 columns and variable x holds the data of the 2nd column to 31st column and variable y holds the data of the first columns.
We drop the last column from our dataset since it contains only null value.
Then from sklearn we import label encoder and transform the first column (1-malignant, 0-benign).
Then we split our data into training (80%) and testing (20%). 
Then we import Linear Regression from sklearn library, and then we find the mean absolute error, mean squared error and root mean square error between y test and y pred.
