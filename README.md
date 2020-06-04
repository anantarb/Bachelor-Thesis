# Title: Scalable Optimal Variable Selection

## Abstract

Variable selection refers to a machine learning technique where we select a subset of relevant variables or features from the data. It is widely used in machine learning to achieve high prediction accuracy and to reduce the model's training time. Many techniques are available to perform variable selection, including best subset selection, forward stepwise regression, forward stagewise regression, and least angle regression. However, the application of these mechanisms to large-scale data is infeasible because the computational complexity of training is very high.
  
Parallelization is a way of designing a computer program such that the sets of instructions execute in parallel. Parallelization helps to solve the scalability problem in machine learning, running array computations in parallel, and reducing the running time of the algorithms. There are several ways of achieving parallelization; however, this guided research focuses on dividing the large array into small arrays and running simultaneous calculations on these small arrays in a distributed system. Distributed parallelization allows us to efficiently remove redundant variables from large-scale data, reducing the training time of variable selection mechanisms, and minimizing computational resources.
  
This research aims to implement state-of-the-art variable selection techniques (least angle regression and forward stagewise regression) using Dask array, and Dask distributed for parallel scalability. It compares the performance of two approaches with respect to the quality of the selected training subsets and parallel scalability on the reference data.
