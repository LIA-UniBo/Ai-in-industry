#  Anomaly detection for self-supervised learning

## Dataset
------------------------------
The data was collected from a monitored supercomputer hosted at CINECA and called "Marconi100"; the data was collected with a tool called Examon.
The dataset is composed of several folders, a folder for each selected node (there are not all the hundreds of nodes present on Marconi100, but some nodes with periods that also contained failures).
The information monitored on Marconi100's nodes is varied, ranging from the load of the different cores, to the temperature of the room where the nodes are located, the speed of the fans, details on memory accesses in writing / reading, etc
The sampling rate of the data at the source varies between 5 and 10 seconds.
However, in the data set the data are aggregated in 15-minutes intervals; in particular, the mean value ("avg: <metric_name>") and variance ("var: <metric_name>") are computed over each 15-minute interval.


## Task
-----------------------------------------
Anomaly detection using self-supervised learning


## Models
-------------------------------------
I have used here models both semi-supervised and unsupervised. In order to make the comparision between the types of the model.
1. Autoencoders
2. Isolation Forest
3. Local Outlier Factor
4. One class SVM
5. Minimum Covariance Determinant

## Project WorkFlow
--------------------------------------------
1. Dataset Prepratation
2. Data Analysis
3. Split the data into training(Normal data)  and testing 
4. MinMax Scaling
5. Implementation Model - Autoencoder
6. Reconstruction error check
7. chosing Threshold based on F1 score
8. Implementation of Unsupervised Algorithms
  * Isolation Forest
  * Local Outlier Factor
  * One class SVM
  * Minimum Covariance Determinant

## How to Run
----------
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/17Z6mLZKr12sZysTfQnWxqUMMTUBHKvvP?usp=sharing)
load the dataset to the folder and provide the folder location to the variable data_dir and run all 

## Built With
---------------------------------
Python 3.7

## Author
-------------------------------
[Jyoti Yadav](https://www.linkedin.com/in/jyoti-yadav-64916b160/)




