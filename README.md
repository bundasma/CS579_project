This repository contains the python files related to my CS579 Deep Learning Final Project. In this project, I followed a Kaggle Competition https://www.kaggle.com/c/PLAsTiCC-2018/overview, where simulated astrophysical observation data was given about astronomical objects and the goal was to classify them. This project required a lot of data, too much for Github to allow uploading, so all of the source data is found on my google drive here: https://drive.google.com/drive/folders/1isDJ5kK8kmooA3AfePqM5jzEO6aaEZMv?usp=sharing 

The maincoding here is all performed in Jupyter notebooks, with minor portions performed in python scripts which are used in the jupyter notebooks. 

The code which contains everything to construct and test the neural network is found in the jupyter notebook DL_project. To run this you will need all of the datafiles found in the google drive folder. Running all of the cells in order will import packages, define functions, process training data, build and train a model, then finally load testing data and run predictions on it, storing them in test_pred.csv. 

These predictions can be evaluated in the evaluations jupyter notebook. Running all of these cells will import the test_pred.csv file, and making use of plasticc_test_metadata, will calculate the competition scores for the predictions. Also in this file, a confusion matrix will be constructed as well.

The third jupyter notebook, lightcurves, is used just for light curve plotting. Running it will look at training and test data, plotting one lightcurve for each class of object.
