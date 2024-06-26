# HMDCNN-Tree

This repository contains the code for "Optimized Visual Recognition through a Deep Convolutional Neural Network with Hierarchical Modular Organization" article by Ade Clinton Sitepu and Chuan-Ming Liu.

## Usage

### Dependencies

- [Python3](https://www.python.org/downloads/)
- [PyTorch(1.1.0)](http://pytorch.org)

Use ``` pip3 install -r ../../requirements.txt ``` to install the dependencies for Python3.

## Directory Structure

- Demo: Contains Jupyter Notebook file that performs inference on sample images.
- Models: Contains trained pytorch models of the modules of the HMDCNN-Tree.
- Softmax Output: Contains the saved softmax output values; required by Mean Softmax Likelihood (MSL).
- Test: Contains scripts to find the accuracy of the HMDCNN-Tree.
- Train: Contains scripts to train the HMDCNN-Tree's modules.
