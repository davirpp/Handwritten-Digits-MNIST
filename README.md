# Handwritten Digits MNIST

> MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

> Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.
 
## Objectives
- Check whether a regular Neural Network has good accuracy in classifying handwritten digits 
- See how good a Convolutional Neural Network can be in classifying handwritten digits
- Compare the results of both architectures

## Dataset
It's available in the following link: https://www.kaggle.com/c/digit-recognizer/data

But can be acessed directly by the Tensorflow Library with this code:
```
from tensorflow.keras.datasets import mnist
(X_train, y_train), (X_test, y_test) = mnist.load_data()
```

## Tools
Although I used Tensorflow to read the dataset, I decided to study and use Pytorch, so in both models I used Pytorch

And if you want, you can download and use the trained models:
- Regular Neural Network: [model_nn.pt](https://github.com/davirpp/Handwritten-Digits-MNIST/blob/main/model_nn.pt)
- Convolutional Neural Network: [model_conv.pt](https://github.com/davirpp/Handwritten-Digits-MNIST/blob/main/model_conv.pt)

## Results
I'll let you see the results and conclusion of this work in the notebook!


Hope you enjoy it!
