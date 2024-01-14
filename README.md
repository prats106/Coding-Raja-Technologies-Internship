# Image Classification on Food Recognition

# Introduction 

In this project , we made a food recognition and calorie estimation system that uses the images of the food, given by the user, to recognize food item and then estimates the calorie present in same food item. Food image recognition is one of the promising applications of visual object recognition in computer vision. The system uses image processing and computational intelligence for food item recognition. We trained a large, deep convolutional neural network to classify the 1000 high-resolution images of each category.

# Prerequisites
It is needed to install pycocotools to execute the notebooks. You can get it from pip or from the original repo To install on Windows, you can use Anaconda environment

# Dataset

The dataset contains a number of different subsets of the full food-101 data. For this reason the data includes massively downscaled versions of the images to enable quick tests. The data has been reformatted as HDF5 and specifically Keras HDF5Matrix which allows them to be easily read in. The file names indicate the contents of the file.. We have used 10 categories in our project. They are Apple Pie, Bibimbap, Cannoli, Edamame, Falafel, French Toast, Ice-Cream, Ramen, Sushi, Tiramisu.

# Results

The best model is the last (called Model D), and it works quite well also at runtime detecting food segmentations from a video with an acceptable frame rate.

# Resources & Libraries

Tensorflow + Keras
