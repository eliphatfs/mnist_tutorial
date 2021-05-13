# mnist_tutorial
A tutorial for MNIST handwritten digit classification using sklearn, PyTorch and Keras.

## Homework Solution Description

### Environment
* Windows 7
* python 3.8.3
* numpy 1.19.2
* matplotlib 3.3.4
* sklearn 0.24.1
* pytorch 1.7.1

### Details
PyTorch is used. Simple NN built is `FC1024` - `FC1024` - `FC10`, with layer normalization and `ReLU` activation.

| Question | Train Acc. (%) | Test Acc. (%) |
| -- | ------ | ------ |
| Q1 | 97.35% | 89.30% |
| Q2 | 81.93% | 80.50% |
| Q3 | 97.83% | 87.60% |
| Q4 | 91.98% | 90.10% |
| Q5 | 98.73% | 97.57% |

# Code structure
* [`numpy_matplotlib_sklearn.ipynb`](numpy_matplotlib_sklearn.ipynb): for numpy, matplotlib and sklearn.
* [`pytorch.ipynb`](pytorch.ipynb): for pytorch.
* [`keras.ipynb`](keras.ipynb): for keras.
* Reference solution: (not published yet)
    * [`numpy_matplotlib_sklearn_solution.ipynb`](numpy_matplotlib_sklearn_solution.ipynb)
    * [`pytorch_solution.ipynb`](pytorch_solution.ipynb)
    * [`keras_solution.ipynb`](keras_solution.ipynb)

# Requirements
Code tested on following environments, other version should also work:
* linux system (ubuntu 16.04) 
* python 3.6.3
* numpy 1.13.3
* matplotlib 2.1.0
* sklearn 0.19.1
* pytorch 0.4.1
* keras 2.1.2
