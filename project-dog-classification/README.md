[//]: # (Image Reference)

[image1]: ./images/sample_dog_output.png "Sample Output"

# Dog-breed Classifier

## Project Overview

It's the Convolutional Neural Network(CNN) project in the Deep Learning Nanodegree program of Udacity. I learned how to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images. Given an image of a dog, my algorithm identifies an estimate of the dog's breed. If supplied an image of a human, the code identifies the resembling dog breed.

![Sample Output][image1]

## Project Instruction

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	```	
		git clone https://github.com/HROlive/Deep-Learning-Nanodegree/project-dog-classification.git
		cd project-dog-classification
	```
2. Open the `dog_app.ipynb`.
	```
		jupyter notebook dog_app.ipynb
	```
3. Read and follow the instructions! This repository doesn't include any dataset you need. You can check out the notebook to download them.

 
## Project Information

### Contents

- Intro
- Step 0: Import Datasets
- Step 1: Detect Humans
- Step 2: Detect Dog
- Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
- Step 4: Create a CNN to Classify Dog Breeds (using Transfer Learning)
- Step 5: Write Your Algorithm
- Step 6: Test Your Algorithm

### Libraries

The list below represents main libraries and its objects for the project.
- [PyTorch](https://pytorch.org/) (Convolutional neural network)
- [OpenCV](https://opencv.org/) (Human face detection)
- [Matplotlib](https://matplotlib.org/) (Plot images)
- [Numpy](http://www.numpy.org/) (Fundamental package for scientific computing)

## (Optionally) Accelerating the Training Process 

If your code is taking too long to run, you will need to either reduce the complexity of your chosen CNN architecture or switch to running your code on a GPU.

#### Amazon Web Services

You can use Amazon Web Services to launch an EC2 GPU instance. (This costs money)
