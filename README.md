# CNN-approach-for-malaria-diagnosis

In this project which is developed on python 3, the goal is classifying infected and uninfected cell images by malaria disease. In order to reach this goal, 15-layer Convolutional Neural Network (CNN) which contains 7 layers of 3 by 3 2D Convolutional layer, 3 layers of 2 by 2 max-pooling layer, 4 layers of dense layer which each layer has 128 neurons with relu activation function and finally a dense layer with two neuron and activation function for this layer is softmax, is proposed. After training, the model accuracy is over 95% on test data. For training of support vector machine, the features, extracted from the last layer with relu activation function, are used. Accuracy of this model reach over 96% on test data. 
## Getting Started

For running this code, you must download CNN_Approach_Malaria_Disease.ipynb on colab machine and have a kaggle token in order to download data on the machine. 

### Prerequisites

Platform:
Python 3

Used libraries: keras, os, random, numpy, PIL, sklearn, zipfile.

## Authors

* **Nima Gozalpour** - *Initial work* - [NimaGozalpour](https://github.com/NimaGozalpour)

