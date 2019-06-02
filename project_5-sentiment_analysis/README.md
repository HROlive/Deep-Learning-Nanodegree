[//]: # (Image Reference)

[image1]: ./images/reviews.png "Reviews"
[image2]: ./images/project_overview.PNG "Project Overview"

# SageMaker Deployment Project

## Project Overview
In this project, I used Amazon SageMaker, AWS Lambda and Amazon API Gateway to develop a complete project from end to end. The result is a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. Bellow you can see some examples of the final result.

![Reviews][image1]

## Project Instruction

### Instruction

1. Clone the repository and navigate to the downloaded folder.
	```
		git clone https://github.com/HROlive/Deep-Learning-Nanodegree/project_5-sentiment_analysis
	```
2. Open the `SageMaker Project.ipynb` file.
	```
		jupyter notebook SageMaker Proejct.ipynb
	```
3. Read and follow the instructions! You can find and download the dataset for this project in the notebook.

## Project Information

### Contents

- General Outline
- Step 1: Downloading the data
- Step 2: Preparing and Processing the data
- Step 3: Upload the data to S3
- Step 4: Build and Train the PyTorch Model
- Step 5: Testing the Model
- Step 6: Deploying the model for testing
- Step 7: Use the model for testing
- Step 6: Deploy the model for the web app
- Step 7: Use the model for the web app

### Project Overview

![Project Overview][image2]

### Libraries

The list below represents main libraries and its objects for the project.
- [Amazon SageMaker](https://aws.amazon.com/sagemaker) (Build, train, and deploy a model)
- [AWS Lambda](https://aws.amazon.com/lambda)  (Function that has permission to send and recieve data from a SageMaker endpoint)
- [Amazon API Gateway](https://aws.amazon.com/api-gateway) (Acts as an interface that lets our web app communicate with the Lambda function)
- [PyTorch](https://pytorch.org) (RNN classifier)

### Delete the Endpoint
Remember to always __SHUT DOWN YOUR ENDPOINT__ if you are no longer using it. You are charged for the length of time that the endpoint is running so if you forget and leave it on you could end up with an unexpectedly large bill.
```
	predictor.delete_endpoint()
```
