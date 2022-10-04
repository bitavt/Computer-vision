# Image classification model via transfer learning
Image classification for classifying pet (cat or dog) with an accuracy of 97% using MobileNetV2, and transfer learning in Tensorflow.
MobileNetV2 is a deep convolutional network with 154 layers and weights pre-trained on ImageNet (containing more than 20,000 categories).



# Object detection using Faster R-CNN and Inception Resnet v2
Object detection using tensorflow hub and tensorflow object detection API.
The model is Faster R-CNN trained on COCO 2017 dataset (where images scaled to 640x640 resolution) with batch size 64, where Inception Resnet v2 (using regular Convolutions) initialized from Imagenet classification checkpoints is used as a feature extractor.
