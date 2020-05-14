# Xor-Neural-Net
A simple 2 layer Neural Net that computes the xor of two two-bit numbers

* __Dataset__ : Two datasets can be used for training, one present in x1.csv which contains 32 minimal distinct data points that cover the entire sample space. Another funtion in the notebook generates a random dataset of a specified size(default:1000) to train the model.
* __Training__ : The model was trained for 300,000 epochs, on an two layer neural network containing 6 hidden-units and 2 output-units with ReLU and Sigmoid activation layers respectively. Learning rate was taken as 0.1 . The complete network is implemented in numpy. Xavier initialization was used for the weights. 
* __Loading__ : The weights and monitoring lists are present in 'mem_dict.txt' and can be loaded. A test function has been implemented that tests the model over 1000 random samples and reports the accuracy.

![](https://github.com/siddarthgopalakrishnan/Xor-Neural-Net/blob/master/Results.png)
