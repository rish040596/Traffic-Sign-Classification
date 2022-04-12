# Traffic-Sign-Classification

In this Deep Learning project, I built a model for the classification of traffic signs images into different categories using a convolutional neural network(CNN) and Keras library.

The image dataset consists of more than 50,000 pictures of various traffic signs(speed limit, crossing, traffic signals, etc.) Around 43 different classes are present in the dataset for image classification. The dataset classes vary in size. Some classes have very few images while others have a vast number of images.

--------------------------------------------------------------------------------------

I followed the below 4 steps to build the traffic sign classification model:

Dataset exploration

CNN model building

Model training and validation

Model testing

--------------------------------------------------------------------------------------

The architecture of my model is:

2 Conv2D layer (filter=32, kernel_size=(5,5), activation=”relu”)
MaxPool2D layer ( pool_size=(2,2))
Dropout layer (rate=0.25)
2 Conv2D layer (filter=64, kernel_size=(3,3), activation=”relu”)
MaxPool2D layer ( pool_size=(2,2))
Dropout layer (rate=0.25)
Dense Fully connected layer (256 nodes, activation=”relu”)
Dropout layer (rate=0.5)
Dense layer (43 nodes, activation=” softmax”)

--------------------------------------------------------------------------------------

Accuracy Obtained - 96.3%
