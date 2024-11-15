# CT_Scan_Prediction
Background: In this assignment you will perform some preliminary analysis of a dataset from the UCI machine learning repository. Some features have been extracted from slices of CT medical scans. There is a regression task: attempt to guess the location of a slice in the body from features of the scan. A little more information about the data is available online2:
https://archive.ics.uci.edu/ml/datasets/Relative+location+of+CT+slices+on+axial+axis
However, you should use the processed version of the dataset given below.

Download the data here (26 MB).

The patient IDs were removed from this version of the data, leaving 384 input features which were put in each of the “X_...” arrays. The corresponding CT scan slice location has been put in the “y_...” arrays. We shifted and scaled the “y_...” location values for the version of the data that you are using. The shift and scaling was chosen to make the training locations have zero mean and unit variance.

The first 73 patients were put in the _train arrays, the next 12 in the _val arrays, and the final 12 in the _test arrays. Please use this training, validation, test split as given. Do not shuffle the data further in this assignment.
