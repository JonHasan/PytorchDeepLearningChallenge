# PytorchDeepLearningChallenge
Pytorch scholarship Program. This file repository includes code for the image Classifier Final project. I trained a resnet152 for 30 + 15 epochs using an adam optimizer. I unfroze the third and fourth layer as well as the avgpool and classifier layers first. I then unfroze the entire network for second round of training. 

## Image Classifier

This is the final project for the pytorch deep learning challenge.

In this notebook, a convolutional neural network is designed using transfer learning to identify flowers from an image dataset.

The neural network used was resnet 152 that was pretrained and had the last classifier layer remade so that the ouptut was the number of flower classes.

The network was trained and then a test score was generated determining how accurate the network was on the dataset.

"Test Score As part of the challenge, you'll be assessed on how well your model performs on a test set of flower images. You'll want to save your trained model as a checkpoint... ."

The network acheived a 99% accuracy through a combination of Adam optimizer, reduceLROnPlateau scheduler and lr modification after each training session.

## Code 

Download the repository to your computer. You will also need to download pytorch and torchvision. 

I personally would recommend downloading an anaconda distribution for your OS and then performing 

`pip install pytorch torchvision`

in a conda environment. Best to keep packages seperate from each other. 

## A return to the past

Thinking about it now in 2021, I kind of feel cheap using a resnet. I know that transfer learning is a valuable thing in deep learning since it can take the weight off of us 
in terms of making our own network but its basically like trying to say 

`import scikit-learn`

Would make me a machine learning engineer. I don't know. 

