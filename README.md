# Deep-Network-Compression
## Compressing Deep Neural Networks using Singular Value Decomposiiton

This work presents an approach to compress deep neural networks by performing singular value decomposition on the weights of the trained network. The compression that we finally achieve reduces the network size by almost 96%. We test this approach on the MNIST dataset, in order to prove its validity. This approach can be taken to much deeper networks, too. 

We start off by training a deep neural network with five fully connected hidden layers with 1024 untis each, to classify the MNIST dataset with a 98% accuracy. Thereafter, we test the accuracy of the same network after performing SVD on its weights, trying out many low-rank approximations of the trained weight matrices. 

Finally, we obtain a D=20 rank approximation of each of the weight matrices, and fine tune the network to achieve almost the same accuracy as that of the original network. 

Hope that you find this interesting!
