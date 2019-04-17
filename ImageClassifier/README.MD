
This is the final project for the pytorch deep learning challenge. 

In this notebook, a convolutional neural network is designed using transfer learning to identify flowers from an image dataset. 

The neural network used was resnet 152 that was pretrained and had the last classifier layer remade so that the ouptut was the number of flower classes. 

The network was trained and then a test score was generated determining how accurate the network was on the dataset. 

"Test Score
As part of the challenge, you'll be assessed on how well your model performs on a test set of flower images. You'll want to save your trained model as a checkpoint... ."

The network acheived a 99% accuracy through a combination of Adam optimizer, reduceLROnPlateau scheduler and lr modification after each training session. 




