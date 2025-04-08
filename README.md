# Using GPU with Pytorch and Tensorflow

This repository demonstrates how we can use GPU with Pytorch and Tensorflow. The code example to use GPU with Pytorch is provided in [pytorch-example-gpu.ipynb](pytorch-example-gpu.ipynb), while the code example to use GPU with Tensorflow is provided in [tensorflow-example-gpu.ipynb](tensorflow-example-gpu.ipynb).

## Installation

To install necessary libraries, you can run the first cell of each notebook.

## Using GPU with Pytorch

To use GPU with Pytorch, we need to move the matrix that we want to compute with GPU acceleration to the GPU memory. We can move the matrix by adding `.to('cuda')` after the variable that stores the matrix. This matrix can be weight matrix of model or data.

## Using GPU with Tensorflow

Using GPU with Tensorflow is less complicated than in Pytorch. You just need to ensure that the installed Tensorflow library support GPU acceleration. This can be done by running the following bash command:

```bash
python3 -m pip install 'tensorflow[and-cuda]'
```
