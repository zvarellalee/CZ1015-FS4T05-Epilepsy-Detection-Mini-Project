# CZ1015-Mini-Project
This repository contains the jupyter notebook for classifying whether an epileptic patient is having a seizure or not, through EEG readings, along with raw data and processed datasets.

# Introduction
Epilepsy is the most common chronical disorder affecting nearly 50 million people worldwide. It is associated with periodic loss of consciousness characterized by recurrent seizures, convulsions and an abnormal electrical activity of the brain. EEG, which is the recording of electrical activity of the brain signals, can be used to diagnose the epilepsy condition.

This project will use binary classification methods to predict whether an individual is having a seizure from the EEG at a point in time.


# Dataset
The original dataset came from the UCI Machine Learning Repository: (https://archive.ics.uci.edu/ml/datasets/Epileptic+Seizure+Recognition)

This dataset records the electroencephalogram (EEG) readings of 500 individuals, classified into 4097 different data readings divided into 23 chunks per individual. Thus, there are 23 x 500 = 11,500 rows of information. Each row has 178 columns representing EEG readings taking place over 1 second. Column 179 represents the label y, which indicates if the patient is having a seizure {1} or not {2,3,4,5}. 




# Problem Statement
We would like to find out how we can best detect epilepsy. Taking our problem and looking at it from a Data science perspective, this is a classification problem, where we are classifying epilepsy cases and non-epilepsy cases. We extrapolated this problem and decided to determine the best model for detecting epilepsy using machine learning. Our metrics was based on classification accuracy and FNR. We set the FNR as an important variable because we want to minimise the number of undetected epilepsy. 


### This project was completed as a mini-project in CZ1015 by Zachary, Wilson, Chi Hui and Sabrina
