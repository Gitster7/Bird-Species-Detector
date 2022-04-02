# Birds Species - Image Classification 🪶

## 1. Problem

To identify the species to which a bird belongs to among the 400 different species that our model was trained on and classify it accordingly. 

## 2. Data
Data set of `400` bird species.`58388` training images, `2000` test images(5 images per species) and `2000` validation images(5 images per species.
All images are `224 X 224 X 3` color images in jpg format. 

Data : https://www.kaggle.com/gpiosenka/100-bird-species?select=EfficientNetB4-BIRDS-0.99.h5

## 3. Model Selection
efficientnet/b4/classification
Imagenet (ILSVRC-2012-CLS) classification with EfficientNet-B4.

model_url: https://tfhub.dev/tensorflow/efficientnet/b4/classification/1



Project Blog: https://omkarvatsa.hashnode.dev/bird-species-image-classification-using-ml
