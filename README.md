# BIRDS-525-SPECIES--image-classification
Classify 525 kinds of birds using CNN 

## About the data
The data set of 525 bird species. 84635 training images, 2625 test images(5 images per species) and 2625 validation images(5 images per species.
the link to the data is here: https://www.kaggle.com/datasets/gpiosenka/100-bird-species 
All images are 224 X 224 X 3 color images in jpg format. The data set includes a train set, test set, and validation set. Each set contains 525 sub-directories, one for each bird species

## summary of methods
For each model, I used the image data generator in keras. I created each model as described below. Each model is compiled using a batch size/samples ratio for the epochs_per_step (on training and validation steps). The compiled models are fit to the generator data for epochs required with a patience of 5. I graphed the validation and training data loss and accuracy as a function of epochs. Finally, the third dataset - test - was compared to the model to give an accurate accuracy and loss value for each fit model.
