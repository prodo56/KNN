# KNN
#### Dataset

Download the python version of CIFAR-10 dataset from the link below: 

https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz.

#### Implementation and execution:

Images are split into training and testing sets. The first N images are used as testing images which are queries for K-NN classifier. The rest of (1000−N) images are used for training. (N is specified as an input argument.)


To execute the program:
> python knn.py K D N PATH/TO/DATA

where D is the reduced dimension of data using PCA.
