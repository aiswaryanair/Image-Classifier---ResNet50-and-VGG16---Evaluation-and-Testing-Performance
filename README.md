# Image-Classifier---ResNet50-and-VGG16---Evaluation-and-Testing-Performance

## Dataset Used
The dataset utilized for this project was sourced from [Concrete Crack Images for Classification](http://dx.doi.org/10.17632/5y9wdsg2zt.2#file-c0d86f9f-852e-4d00-). It presumably contains images relevant to concrete crack classification.

## Objective
The project is done as part of course completion of IBM AI Engineering Professional Certification

## Models
ResNet50 - Residual Network (ResNet) is a deep learning model used for computer vision applications. It is a Convolutional Neural Network (CNN) architecture designed to support hundreds or thousands of convolutional layers.
VGG16 - It is a convolution neural network (CNN) model supporting 16 layers.

## Required Libraries
```python
import keras
from keras.models import Sequential
from keras.layers import Dense
from keras.applications import ResNet50
from keras.applications.resnet50 import preprocess_input
from tensorflow.keras.applications.vgg16 import VGG16
from tensorflow.keras.applications.vgg16 import preprocess_input
from keras.preprocessing.image import ImageDataGenerator


