# Dogs-vs-Cats-Classifier
This is simple classifier for binary classification of Dogs and Cats images with deep learning.
The dataset used here contains 25,000 images of cats and dogs in seperate folders for both the categories.
The classifier is a simple convolutional neural network to classify the images.
The model uses Tensorflow 2.0

The  loss and accuracy acheived on the test data is as follows:
loss: 0.3733 - accuracy: 0.8446

Model Architecture:
Input Data Shape: 64x64x1 (loaded the images in Gray Scale)

Layer 1:

Convolutional Layer Filters: 64  

Filter shape: 3x3

Activation Function: ReLu

Max Pooling Pool shape: 2x2

Layer 2:

Convolutional Layer Filters: 64 

Filter shape: 3x3

Activation Function: ReLu

Max Pooling Pool shape: 2x2

Layer 3:

Convolutional Layer Filters: 64 

Filter shape: 3x3

Activation Function: ReLu

Max Pooling Pool shape: 2x2

Classification:

Flatten

Dense Size: 1

Activation Function: Sigmoid

Optimizer: Adam,
Loss: Binary Crossentropy,
Metrics: Accuracy
