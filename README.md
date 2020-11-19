# Fake-vs-Real-Image-Detection-Challenge
Great Lakes AIML Hackathon Challenge to detect Fake Images generated by GANs from authentic images.
---
This solution was adjudged the winner of 'Hack of All Trades' Hackathon conducted by Great Learning on 7-8th November 2020. 

The repository contains 2 solutions:
- A custom solution designed by us, which involved Image Augmentation, multiple callbacks & a custom CNN comprising of multiple Convolution Layers, Maxpooling Layers, Dropout & Batch Normalization; with ReLU activation function & ADAM optimizer. This file is labelled: 
### Fake_vs_Real_Image_Detection_Challenge_withCustomCNN
- A Transfer Learning architecture using Resnet50 (without the Fully-Connected Layers) & custom Fully-Connected Layers with Dropout & Batch Normalization; with ReLU activation function & ADAM optimizer. This too has Image Augmentation, alog with Resnet50 specific Image Preprocessing & multiple callbacks. This file is labelled: 
### Fake_vs_Real_Image_Detection_Challenge_withResNet50.

---
## Background:
---
With the rise of electronic media in the form of social media primarily, there has been a lot of misinformation spread in the form of images which are artificially created using modern
augmentation tools. In order to segregate legitimate information from artificially created images, it is important to use modern technological advances to stop the spread of misinformation.
The Fake vs Real Image Detection Challenge draws inspiration from the above mentioned misrepresentation of data and tries to solve this problem using computer vision techniques.
Fake and Real images have been provided and we need to build a model that can segregate test images into Fake and Real Images. A mobile application or a software integrated into the
mobile’s operating system can be built using this technology which can segregate fake images from real ones.

## Goal:
---
The goal of this hackathon was to build a model that can accurately distinguish between fake and real images using the provided images for training. The images provided belong to two classes
comprising of original pictures that were actually clicked using cameras and fake images that were artificially created using Generative Adversarial Networks(GANs).

## Dataset and Files Information:
---
The dataset comprises of 1709 training images segregated into separate folders for fake images and real images, and 332 test images. We were also provided with a train.csv file which contained the labels for each photo in the training set
and test.csv file containing names of all images in the test folder. A sample_submission.csv file had been provided to help submit our predictions against the
file names in the test folder.

## Evaluation Metric:
---
Accuracy - Total number of correct predictions/ Total number of data samples

## Submission Format
---
We needed to submit the csv format file with 2 columns in the order -
file_id and label using the test dataset.
