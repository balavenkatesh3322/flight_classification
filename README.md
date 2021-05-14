# Flight Classification
Deep learning model to classify flight images.

## Dataset

I have prepared the following three kinds of images. Here is the dataset [link](https://drive.google.com/drive/folders/1nxuB7sUnUIaj8keUQfPeEy-HCUqziwUR?usp=sharing)

* helicopter
* passenger-plane
* rocket

## Deep learning model

I am using a pre-trained [ResNet50](https://github.com/fchollet/deep-learning-models/blob/master/resnet50.py) model to train the model with an above dataset. I have fine-tuned the ResNet50 model to work with our custom dataset. I have trained the model. You can download the flight classification model [here](https://drive.google.com/drive/folders/1nwh_nsuDCW-bA7k9zR2tiuh8LXwTCcNf?usp=sharing)

## How to check model accuracy

You can checkout **Flight Prediction.ipynb** Colab Notebook to see the image prediction results.

## Model Performance(Confusion Matrix)

<img src="./confusion_matrix.png" width="500" height="300">
