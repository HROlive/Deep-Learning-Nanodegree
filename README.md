# [Deep Learning Nanodegree Program](https://www.udacity.com/course/deep-learning-nanodegree--nd101)

## Program Summary

Become an expert in neural networks, and learn to implement them using the deep learning framework PyTorch. Build convolutional networks for image recognition, recurrent networks for sequence generation, generative adversarial networks for image generation, and learn how to deploy models accessible from a website.

This repository contains the projects that I've developed during [this program.](https://www.udacity.com/course/deep-learning-nanodegree--nd101).

## Projects

Project 1 : [Predicting Bike-Sharing Patterns](https://github.com/HROlive/Deep-Learning-Nanodegree/tree/master/project_1-bikesharing)
-
![Project 1_Predicting Bike-Sharing Patterns](https://user-images.githubusercontent.com/14244685/55161620-2c301580-5190-11e9-8947-4535a4993201.PNG)

In this project, I have implemented a neural network in Numpy to predict bike rentals.

Project 2 :  [Dog Breed Classifier](https://github.com/HROlive/Deep-Learning-Nanodegree/tree/master/project_2-dog-classification):
-
![dog breed](https://user-images.githubusercontent.com/14244685/56671322-40efc280-66d6-11e9-80b6-3a2fd9657d10.PNG)

In this project, I have built a convolutional neural network with PyTorch to classify any image (even an image of a face) as a specific dog breed.

Project 3 :  [TV Script Generator](https://github.com/HROlive/Deep-Learning-Nanodegree/tree/master/project_3-tv-script-generation): 
-
![Generating TV script](https://user-images.githubusercontent.com/14244685/56514538-5b4f6200-6557-11e9-9235-084928059a5a.PNG)

In this project, I have trained a recurrent neural network to generate scripts in the style of dialogue from Seinfeld.

Project 4 :  [Face Generation](https://github.com/HROlive/Deep-Learning-Nanodegree/tree/master/project_4-face_generation): 
-
![Face Generation](https://user-images.githubusercontent.com/14244685/56671622-cbd0bd00-66d6-11e9-9a8d-d8b8725a054e.PNG)

In this project, I have used a DCGAN on the CelebA dataset to generate images of new and realistic human faces.

Project 5 :  [Sentiment Analysis SageMaker Deployment](https://github.com/HROlive/Deep-Learning-Nanodegree/tree/master/project_5-sentiment_analysis): 
-
![Sentiment Analysis](https://www.marketmotive.com/market_motive/sentiment-analysis.jpg)

In this project, I used Amazon SageMaker, AWS Lambda and Amazon API Gateway to develop a complete project from end to end. The result is a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews.

---

# Dependencies

## Configure and Manage Your Environment with Anaconda

Per the Anaconda [docs](http://conda.pydata.org/docs):

> Conda is an open source package management system and environment management system 
for installing multiple versions of software packages and their dependencies and 
switching easily between them. It works on Linux, OS X and Windows, and was created 
for Python programs but can package and distribute any software.

## Overview
Using Anaconda consists of the following:

1. Install [`miniconda`](http://conda.pydata.org/miniconda.html) on your computer, by selecting the latest Python version for your operating system. If you already have `conda` or `miniconda` installed, you should be able to skip this step and move on to step 2.
2. Create and activate * a new `conda` [environment](http://conda.pydata.org/docs/using/envs.html).

\* Each time you wish to work on any exercises, activate your `conda` environment!

---

## 1. Installation

**Download** the latest version of `miniconda` that matches your system.

|        | Linux | Mac | Windows | 
|--------|-------|-----|---------|
| 64-bit | [64-bit (bash installer)][lin64] | [64-bit (bash installer)][mac64] | [64-bit (exe installer)][win64]
| 32-bit | [32-bit (bash installer)][lin32] |  | [32-bit (exe installer)][win32]

[win64]: https://repo.continuum.io/miniconda/Miniconda3-latest-Windows-x86_64.exe
[win32]: https://repo.continuum.io/miniconda/Miniconda3-latest-Windows-x86.exe
[mac64]: https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh
[lin64]: https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
[lin32]: https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86.sh

**Install** [miniconda](http://conda.pydata.org/miniconda.html) on your machine. Detailed instructions:

- **Linux:** http://conda.pydata.org/docs/install/quick.html#linux-miniconda-install
- **Mac:** http://conda.pydata.org/docs/install/quick.html#os-x-miniconda-install
- **Windows:** http://conda.pydata.org/docs/install/quick.html#windows-miniconda-install

## 2. Create and Activate the Environment

For Windows users, these following commands need to be executed from the **Anaconda prompt** as opposed to a Windows terminal window. For Mac, a normal terminal window will work. 

#### Git and version control
These instructions also assume you have `git` installed for working with Github from a terminal window, but if you do not, you can download that first with the command:
```
conda install git
```

**Now, we're ready to create our local environment!**

1. Clone the repository, and navigate to the downloaded folder.

2. Create (and activate) a new environment, named `deep-learning` with Python 3.6. If prompted to proceed with the install `(Proceed [y]/n)` type y.

	- __Linux__ or __Mac__: 
	```
	conda create -n deep-learning python=3.6
	source activate deep-learning
	```
	- __Windows__: 
	```
	conda create --name deep-learning python=3.6
	activate deep-learning
	```
	
	At this point your command line should look something like: `(deep-learning) <User>:deep-learning-v2-pytorch <user>$`. The `(deep-learning)` indicates that your environment has been activated, and you can proceed with further package installations.

3. Install PyTorch and torchvision; this should install the latest version of PyTorch.
	
	- __Linux__ or __Mac__: 
	```
	conda install pytorch torchvision -c pytorch 
	```
	- __Windows__: 
	```
	conda install pytorch -c pytorch
	pip install torchvision
	```

6. Install a few required pip packages, which are specified in the requirements text file (including OpenCV).
```
pip install -r requirements.txt
```

7. That's it!

Now most of the `deep-learning` libraries are available to you. Very occasionally, you will see a repository with an addition requirements file, which exists should you want to use TensorFlow and Keras, for example. In this case, you're encouraged to install another library to your existing environment, or create a new environment for a specific project. 

Noe, assuming your `deep-learning` environment is still activated, you can navigate to the main repo and start looking at the notebooks:

```
cd
cd ***YOUR PROJECT REPOSITORY***
jupyter notebook
```

To exit the environment when you have completed your work session, simply close the terminal window.
