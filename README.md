# CS439-DCASGD
This repository contains all the code needed to reproduce the results of our study about the Delay Compensated Asynchronous Stochastic Gradient Descent (DCASGD) algorithm's performance. This project was proposed in the scope in the Optimization for Machine Learning course (CS-439) from EPFL during the spring semester of 2022. Our team explored the performance of DCASGD by testing several deep neural networks architectures, several datasets and several machine learning problems

## :raised_hands: Team Members
- Bastien Golomer (PH-MA4)
- Arthur Brousse (SC-MA2)
- Tatiana Cogne (SC-MA2)

## :memo: Repository description
The repositoty counts all the jupyter notebooks used to get the 

## :arrows_clockwise: How to run the code 
In order to run the code, please install the latest version of Jupyter Lab, jupyter or directly run in colab. Some notebooks were coded in colab and thus contain a mounting step. If you want to run the notebooks locally, please comment this line.

If you have access to a cluster of GPU, please make sure to make the appropriate modifications to the code. Particularly, make sure to update the **context** variable to consider the gpus available and which to use, as well as the distribution of the training data. Moreover, check the compatibility of your CUDA toolkit and cuDNN versions with mxnet (this is what restrained us).


## :open_file_folder: Libraries used
 (please use the last version of each package to avoid conflicts)
- numpy 
- mxnet-cu110
- matplotlib
- sklearn
- tqdm
- pytictoc
- gluonnlp
- shap
- scikit-plot
