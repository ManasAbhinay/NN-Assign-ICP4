# NN-Assign-ICP4

# Deep Learning Image Classification with CNN

## Use Case Description
### Image Classification with CNN
1. Training the model
2. Evaluating the model

## Programming Elements
1. About CNN
2. Hyperparameters of CNN
3. Image classification with CNN

## In-Class Programming
    - Convolutional input layer: 32 feature maps, size 3×3, rectifier activation function
    - Dropout layer: 20%
    - Convolutional layer: 32 feature maps, size 3×3, rectifier activation function
    - Max Pool layer: size 2×2
    - Convolutional layer: 64 feature maps, size 3×3, rectifier activation function
    - Dropout layer: 20%
    - Convolutional layer: 64 feature maps, size 3×3, rectifier activation function
    - Max Pool layer: size 2×2
    - Convolutional layer: 128 feature maps, size 3×3, rectifier activation function
    - Dropout layer: 20%
    - Convolutional layer: 128 feature maps, size 3×3, rectifier activation function
    - Max Pool layer: size 2×2
    - Flatten layer
    - Dropout layer: 20%
    - Fully connected layer: 1024 units, rectifier activation function
    - Dropout layer: 20%
    - Fully connected layer: 512 units, rectifier activation function
    - Dropout layer: 20%
    - Fully connected output layer: 10 units, Softmax activation function

2. Predict the first 4 images of the test data using the above model. Then, compare with the actual label for those 4 images to check whether the model has predicted correctly.

3. Visualize Loss and Accuracy using the history object.


