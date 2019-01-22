# Prequisites

I assume that you have basic knowledge of virtual environment in python and you are running this script on Ubuntu 16.04.

If you do not know about the virtual environment you can learn about it here 

>>> https://www.geeksforgeeks.org/python-virtual-environment/

>>> https://conda.io/docs/user-guide/tasks/manage-environments.html

If you are on windows, please do not run the script.

# Set up Tensorflow GPU

This script will install the following things on your system :-


=> Anaconda3-5.0.1
=> Nvidia Driver 390
=> Cuda 9.0
=> CudNN 7.1.4 for CUDA 9.0
=> Tensorflow 1.12.0 


It will create a virtual environment 'env' on your system with Python 3.6


# Steps to run the script 

Run the following commands on the system


>>> git clone https://github.com/om06/setup-tensorflow-gpu.git

>>> bash ~/setup-tensorflow-gpu/setup.sh

When asked for the CudNN path go to the following link, perform the following step to get the download link

Step 1 : Go to this link := https://developer.nvidia.com/rdp/cudnn-archive

Step 2 : Click on Download cuDNN v7.1.4 (May 16, 2018), for CUDA 9.0

Step 3 : Than Copy Download link of cuDNN v7.1.4 Library for Linux

Paste the download link in the terminal and hit enter

When setup is complete the script will reboot the system so that the new changes will reflect in the system

# Enable the virtual environment 

>>> source activate env# ubiquitous-computing-machine-gpu
