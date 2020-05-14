# Dog Breed Classifier #

# Project Overview #
This project uses Convolutional Neural Networks (CNNs) and transfer learning in order to build a pipeline to process real-world, user-supplied images. Convolutional Neural Networks (CNNs) are commonly used to analyse image data. Transfer learning is a technique that allows to reuse a model across different tasks. The objective is that given an image of a dog, the algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed. If the algorithm can't identify the image as a human or dog, it will say so.

# Table of Contents #

Libraries

File Descriptions

Content

Libraries

Keras

OpenCV

Matplotlib

Numpy

# File descriptions #

dog_app.ipynb: Jupyter notebook containing the algorithm and process used to create it.

dog_app.pdf: A copy of dog_app.ipynb in pdf format.

Haarcascades folder: Xml file for use with the OpenCv face detector class.

Various images: Images in jpg and jpeg format used to test the algorithm's predictions.

# Contents #
The project is organized along the following steps:

# Intro #

Step 0: Import Datasets

Step 1: Detect Humans

Step 2: Detect Dog

Step 3: Create a CNN to Classify Dog Breeds (from Scratch)

Step 4: Create a CNN to Classify Dog Breeds (using Transfer Learning)

Step 5: Write Your Algorithm

Step 6: Test Your Algorithm


I used Resnet50 pre-trained for dog detection and if found then used our version Resnet50 trained model to identify the breed.
I used face detector to detect human face if found then used our version of Resnet50 to identity the resembling breed.
The output is much better than I expected. it gives the same breed type to a human who looks the same. even it gives the correct breed of dog in a picture where human was with her.
Model architecture that uses part of a pre-trained model with accuracy on the test set of 80%.

The blogpost can be found on : https://medium.com/@abimbolamuritala65/dog-breed-classifier-dsnd-capstone-project-f798d0f9836
