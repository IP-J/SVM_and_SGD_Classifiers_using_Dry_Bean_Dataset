# Dry_Bean_Dataset
In this notebook, we will learn to develop Python code for a small classification task using the Dry Bean dataset supplied on the UCI Machine Learning webpage: 
http://archive.ics.uci.edu/ml/datasets/Dry+Bean+Dataset

Click on the Data Folder link there and download the DryBeanDataset.zip file. After unzipping the file, you should see 3 files in a subdirectory named DryBeanDataset. 
You only need the Dry Bean Dataset.xlsx file for this Python code.

Tasks done in this notebook are as follows:
1.	Reading the spreadsheet file, inspecting what the columns are by displaying the first few lines of the file, displaying the different features (or columns). 
    Selecting 6 interesting features and illustrating the scatter matrix of these 6 features.
2.	Use the train_test_split function(80/20 split) to randomly split the data to form a training set and a testing set, and 
    displaying the number of instances are in your training and testing sets
3.	Performing feature scaling step on the training set using the StandardScaler class and the fit, fit transform, and transform functions.
4.	Using the Support Vector Classifier from the sklearn.svm.SVC class to perform oneversus-one binary classification on the training set with appropriate hyperparameters,
    and displaying the confusion matrix on the testing set using plot confusion_matrix function.
5.	Repeat step #4 above using the Stochastic Gradient Descent Classifier from the SGDClassifier class.
6.	Comparing the confusion matrices of the two classifiers and giving a brief discussion about your experimental results.
