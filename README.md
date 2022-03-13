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
Anomaly detection for self-supervised learning


## Models
-------------------------------------



## Project WorkFlow
--------------------------------------------



## How to Run
----------
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/17Z6mLZKr12sZysTfQnWxqUMMTUBHKvvP?usp=sharing)


## Built With
---------------------------------
Python 3.7

## Author
-------------------------------
[Jyoti Yadav](https://www.linkedin.com/in/jyoti-yadav-64916b160/)




