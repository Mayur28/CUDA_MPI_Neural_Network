# Implementing a Neural Network from Scratch Using CUDA and MPI
<p align ="center" >
 <img src= "https://user-images.githubusercontent.com/26574827/135074233-78f18c61-99e0-4b7d-9916-26964da7da0e.jpg" height="200px" width = "900px"/>  
 </p>


This project was developed by my colleague and I in which we attempt to investigate the benefit of using parallel programming frameworks as part of our Honours (postgraduate) project. CUDA and MPI were the 2 parallel programming frameworks that we considered.
A neural network served as an ideal candidate for investigating the benefit of parallelization due to the high level of parallelism present in neural networks. Specifically, each node in a layer performs a convolution operation that is independent of the operations performed by other nodes. 
To verify the correctness of our implementation, we used the [UCI Heart Disease](https://www.kaggle.com/ronitf/heart-disease-uci) dataset and recorded the accuracy.

## Results

Please refer to our report (included in this repo) for further details pertaining to all experiments conducted and the results.

## Execution

Considering that the MPI and CUDA solutions are independent, instructions on how to execute each implementation is specified in the readme.txt file in the respective directories.
