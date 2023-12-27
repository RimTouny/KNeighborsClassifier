KNeighborsClassifier
KNN Classifier for Car Evaluation Dataset: Explored impact of training sample sizes &amp; optimal K value selection. Python implementation in a Machine Learning course project (uOttawa 2023).


K-Nearest Neighbors (KNN) Classifier for Car Evaluation Dataset

This repository contains Python code implementing a KNN classifier for the car-evaluation dataset as part of a Machine Learning course project at the University of Ottawa in 2023.

Key Tasks:
Data Preparation: Shuffled the dataset of 1728 samples into a training set (1000 samples), a validation set (300 samples), and a testing set (428 samples) using Python.
Preprocessing: Transformed string attribute values into numerical representations to enable distance-based metrics for KNN, such as Euclidean distance.
Impact of Training Samples: Explored the influence of different training sample sizes (10% to 100% of the training set) on model performance, measuring accuracy on both validation and test sets.
Optimal K Value: Determined the best K value (1 to 10) using the entire training set and plotted an accuracy curve on the validation set to showcase its effect on the KNN classifier's performance.
