# Dog-Breed-Classifier
CNN Project [Udacity Deep Learning Nanodegree]

# Project Overview:
This repo contains all my work for Project 1 of Udacity's Neural Network Foundation Nanodegree Program. In this project, I have learned how to build a pipeline to process real-world, user-supplied images. Given an image of a dog, my algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed. Along with exploring state-of-the-art CNN models for classification, I have made important design decisions about the user experience for our app. By completing this lab, I understood the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline. Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer.

# Table_of_Contents:
1.Libraries
2.File Descriptions
3.Content
4.Results

# Libraries_Files:
* Keras
* pandas
* OpenCV
* Matplotlib
* Numpy
* glob

# File_descriptions:
dog_app.ipynb: Jupyter notebook containing the algorithm and process used to create it.
dog_app.html: A copy of dog_app.ipynb in html format.
Haarcascades folder: Xml file for use with the OpenCv face detector class.
Various images: Images in jpg and jpeg format used to test the algorithm's predictions.
Contents

The project is organized along the following steps:

Step 0: Import Datasets
Step 1: Detect Humans
Step 2: Detect Dogs
Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
Step 4: Use a CNN to Classify Dog Breeds (using Transfer Learning)
Step 5: Create a CNN to Classify Dog Breeds (using Transfer Learning)
Step 6: Write your Algorithm
Step 7: Test Your Algorithm

# Results:
1.The model achieved a test accuracy of 87.27% of the model and above the 60% established accuracy threshold.

2.Some of the breeds have similar colors and shapes but differ in size,is the case between a Beagle and a Pointer or American Foxhound. Therefore the model needs to pick up subtle differences between similar breeds.

3.The model could use some improvements on its ability to classification of the pictures with noise. This is probability to the images was trained.

4.The model predicted the same two or three breeds when identifying an image as persion,Therefore more variety is needed concerning the type of breeds the model predicts in the  persion.

 


# Licensing, Authors, Acknowledgements:
Credits must be given to Udacity for  starter codes and data images useing by this project.
