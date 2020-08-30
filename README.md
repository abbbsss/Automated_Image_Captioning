# Automated Image Captioning

This project contain the implementation of Image captioning task. For this task I have used the Flickr8K dataset which is available at Kaggle. Flickr8K dataset contains 8000 images. Each image in the dataset have 5 different caption for the image.Out of 8000 images 6000 are chosen fro training and 1000 for test and 1000 validation set each.
I have used ResNet50 convolution neural network to extract features from the image and Long short term memory (LSTM) RNN to predict caption. Used Glove vector embedding to represent the word into more comparable features to better predict the next word in the caption.The feature vector from the Resnet and RNN output is further fed into the fully connected network to extract most probable caption for corresponding image.
