# CYSE-499-sentiment-classifier-step-1+2
Step 1 for the movie sentiment classifer assignment

The first cell in the notebook file installs the necessary modules/libraries, running this installs numpy, joblib, scikit-learn, pandas, and matplotlib, once this cell is ran, restart the notebook kernel.

The notebook will load the training and public test data then examines the class distribution. Based on this it splits the training data into training and validation sets and converts reviews into text features.

Next comes the training of the logistic regression classifier, using balanced class weights to account for the imbalance within the given training set, the classifier uses L2 regularization to reduce the overfitting that would commonly occur with smaller training sets. Afterwards, it will evaluate the classifier on the public test data and creates a confusion matrix as well as calculating accuracy. Once trained the model is saved to the model_checkpoint folder and the public_test_predictions.csv file is created.

Required files to reload the trained model are within the model checkpoint folder named 'sentiment_model.joblib'


(apologies for some formatting issues, this was my first time creating a github repository for an assignment)
