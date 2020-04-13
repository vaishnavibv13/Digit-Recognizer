# Digit Recognition
## Problem statement

MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision.
This project will identify digits from a dataset of tens of thousands of handwritten images.



### Data Collection & Cleaning

Data is obtained from kaggle challenge(https://www.kaggle.com/c/digit-recognizer)

The data files train.csv and test.csv contain gray-scale images of hand-drawn digits, from zero through nine.Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.The training data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.

The test data set, (test.csv), is the same as the training set, except that it does not contain the "label" column.



### Modeling
 This step creates a 2D convulution neural network model with 30 epochs.<br><br>
 
 
