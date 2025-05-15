# Project-MLBigData
# https://learn.inside.dtu.dk/d2l/le/lessons/242635/topics/904282
___
## Project Description

### Goal
The overall goal of the project is to build a supervised classification model that can identify a country based on its national flag image.

### Data
The dataset used are the <a href="https://www.kaggle.com/datasets/hamidmahmoodpour/countries-flag-classification">country flags from Kaggle</a>. There are 204 classes in total. The classes have around 500-1500 images each and are divided into X% training, X% validation and X% testing.

### Model/framework
We are planning to use “Hugging Face Transformers” or “PyTorch Image Models (TIMM)” to access and work on pre-trained image classification models. We can also try to incorporate PyTorch Lightning to our workflow to minimize boilerplate code and make it more streamlined. We first plan to use a pre-trained ResNet model with appropriate size. However, we may experiment on Vision transformer (ViT), or ConvNeXt models.

___
## #TODO
* [x] Create a git repository
