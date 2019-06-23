# Research work on Point clouds
The given jupyter notebooks list various approaches to find local reference vectors through a point cloud input
Basic Idea is to train a neural network based on a cluster of 1500 points and its consecutive local reference frames and use them to predict new LRF's.

Best accuracy so far is obtained using Resnet-50 with minor changes.
Convolutions have been changed to Conv1D contrary to Conv2D of original resnet as reading point cloud data 
of 1500x3 matrices is more convenient for resnet.

