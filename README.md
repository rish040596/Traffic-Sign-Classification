# Traffic-Sign-Classification

In this Deep Learning project, I have built a model for the classification of traffic signs available in the image into many categories using a convolutional neural network(CNN) and Keras library.

The image dataset is consists of more than 50,000 pictures of various traffic signs(speed limit, crossing, traffic signals, etc.) Around 43 different classes are present in the dataset for image classification. The dataset classes vary in size like some class has very few images while others have a vast number of images. The dataset doesn’t take much time and space to download as the file size is around 314.36 MB. It contains two separate folders, train and test, where the train folder is consists of classes, and every category contains various images.

--------------------------------------------------------------------------------------

I have followed the below 4 steps to build the traffic sign classification model:

Dataset exploration

CNN model building

Model training and validation

Model testing

I have built a CNN model to classify the images into their respective categories.

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
