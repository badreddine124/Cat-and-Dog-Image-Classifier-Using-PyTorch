# Building an Image Classification of Dog/Cat Dataset implemented by Convolutional Neural Network (CNN)


Classifies an image as containing either a dog or a cat (using Kaggle's <a href="https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/data">public dataset</a>), but could easily be extended to other image classification problems.

### Dependencies:
- PyTorch / Torchvision
- Numpy
- PIL

## Data

The data directory structure I used was:

* project
  * data
    * train
      * dogs
      * cats
    * validation
      * dogs
      * cats
    * test
      * test

## Model Perfomance Sumary
Our model has the accuracy of 97.79 % for the train dataset and 97.32 % for the test dataset.
