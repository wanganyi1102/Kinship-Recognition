# Kinship Recognition

Original dataset and challenge description can be found at [Northeastern Smile Lab - Recognizing Faces in the Wild (kaggle)](https://www.kaggle.com/competitions/recognizing-faces-in-the-wild/submissions)

This repository contains the implementation of Siamese Network for kinship recognition as well as ensemble learning methods. We experimented with transfer learning with: 
- ResNet-50
- SE-Resnet-50
- VGG-16
- EfficientNet-B4
- InceptionV3
- FaceNet
Detailed experiments and results can be found in [Report](group28_report.docx) and introductory video can be found at [link](https://youtu.be/3aczG7i0ycI).

Our ensemble model has achieved Top 20% on the kaggle leaderboard. 

Skills involved: Tensorflow, Keras

### Requirements:
- keras 2.2.4
- tensorflow 1.x
- h5py 2.10.0
