# cv-zoo
Loose collection of computer vision algorithms

## Notebooks
Some Jupyter Notebooks each with a major breakthrough architecture in computer vision with convolutional neural networks

- LeNet5: First CNN architecture from Yann LeCun (http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf)

## Installation
All necessary dependencies can be easily installed using either Anaconda or (the more lightweight) Miniconda. Especially if you want to use tensorflow with a gpu this installation is much easier than using pip and highly recommened.

Download and install Anaconda (https://www.anaconda.com/distribution/)

Create a new virtualenv and install tensorflow-gpu
```
conda create --name tf_gpu tensorflow-gpu 
```
or tensorflow with cpu
```
conda create --name tf_gpu tensorflow
```
Additional package can be installed via
```
conda install <<packagename>>
```
