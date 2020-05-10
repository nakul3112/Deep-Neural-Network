# Deep-Neural-Network
Implementation of Deep Neural Network for image classification


## Overview:

This repository contains implementation for Deep Neural Network on the given dataset for image classification. It includes following steps:

- Loading necessary packages.
- Implementing utility functions to convert images to dataset.
- Implementing functions for ReLU activation, forward propogation and backward propagation.
- Implementing optimization and prediction functions.
- Generalizing for L-Layer network
- Training the model with training dataset.
- Testing the accuracy of model with test dataset.




## Dependencies:

To run this project, you need to have deep learning setup in your local machine.


## Windows:

Follow the instruction [here](http://inmachineswetrust.com/posts/deep-learning-setup/) to install conda on windows.

After following the above instructions, you need to install pillow and pytables into the conda deeplearning environment:
 - Make sure deeplearning environment is active:
   `activate deeplearning`
 - Then, run following commands: 
   
   `conda install pillow`
   
   `conda install pytables`

   `conda install h5py`

## Ubuntu

Follow the steps in this link [here](https://medium.com/@iamHarin17/how-to-setup-a-python-environment-for-deep-learning-with-anaconda-f65ab78a362) to setup a deep learing environment in Ubuntu .



## Instructions to run the project:

After setting up deep learning environment, follow these steps to run the .ipynb file that contains code for logistic regression.

-  `git clone https://github.com/nakul3112/Deep-Neural-Network.git`
-  Ubuntu: `conda activate <environment-name>`

     Windows: `activate <environment-name>`

     Replace the environment name above with the name of your deep learning environment.
-  Run jupyter notebook after opeinmg the terminal in the cloned repository.
     `jupyter notebook`
-  Navigate to the .ipynb file and run the kernel.


