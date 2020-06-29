# Project5-Dog-Breed-Recognition

# Overview

Looking to adopt a dog? Think about what kind of dog you want to adopt, different breeds of dogs can have drastically different personalities and characteristics. Some dog breeds require more maintenance than others. Scrolling through SPCA's website you'll find a lot of dogs up for adoption, but some of them are labeled mixed breed or unknown. This can be one of the reasons why 1 in 10 dogs are returned to the shelter after 6months. Many owners may not have expected the dog to be so expensive and require so much attention. To more efficiently find a forever home for dogs in shelters, I decided to build a dog breed recognition system. 

# Dataset

I used the dataset from Kaggle which contains more than 10,000 images of 130 different dog breeds. Each breed contains roughly 70-150 images. I split the images into train and test set. 

# Findings

I decided to build sequential convolutional neural networks. However, the accuracy was only slightly higher than a guess. I decided to use transfer learning instead. Using VGG19 and ResNet50 I build a convolutional neural network that has a 80% accuracy at identifying the dog breed of an image of a dog. 
