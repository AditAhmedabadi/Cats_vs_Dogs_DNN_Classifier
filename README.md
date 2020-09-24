# Cats-vs-Dogs-DNN-Classifier
This is a Binary DNN Convnet classifier on the cats vs dogs dataset from kaggle. I have used image augmentation to solve the problem for overfitting.

Kaggle Dataset Link : https://www.kaggle.com/c/dogs-vs-cats

Many image augmentation techniques used like horizontal flip , shear_range , zoom_range , rotation_range , width and height shift'

The model is made up of exactly 3 Convolutional layers of 3x3 16,32,64 filters each followed by a max pooling of 2x2 and this if followed by a hidden dense layer of 512 neurons and relu activation function. Then there is an output layer of 1 neuron for binary classifier using sigmoid function (1/1+e^-x)
