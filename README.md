# Udacity Data Scientist Capstone Project : Dog Breed Classifier

### **Instructions**:

Run the notebook dog_app.ipynb.

### **Project Motivation**:

This project is one of the possible capstone projects of Udacity's Data Scientist Nanodegree.
A face detector function and a dog detector function are able to output as a boolean value (True or False)
if a human face/dog is detected on an image. 

In this project, we build a Convolutional Neural Network (CNN) that is able to classify dogs into 133 breeds. 
First, we create a CNN from scratch using layers such as Conv2D and MaxPooling2D and in a later stage we use Transfer Learning on 
the models VGG16 and Inception.

The objective of the project is to combine the face and dog detector function with our CNN that we created through Transfer Learning in
order to determine a) if a dog is detected on an image and if so, what is the most probable breed b) if a human is detected on an image and
if so, what is the dog breed that would most resemble the image and c) if neither a dog nor a face are detected on the image, we output
that no dog nor face could be found.

  
### **Libraries**:
Python3

Here are the libraries I used in my Jupyter Notebook:

Pandas
Numpy
Keras
OpenCV
Matplotlib


### **File Descriptions**:

dog_app.ipynb: Jupyter notebook which contains the dog human classifier algorithm and process used to create it.
dog_app.html: Copy of dog_app.ipynb in html format.
haarcascades folder: Xml file for use with the OpenCv face detector class.
different images: Images in jpg format for testing the predictions of the algorithm.

### **Structure**:
The structure of the project is as follows:

Introduction
Step 0: Import datasets
Step 1: Detect Humans
Step 2: Detect Dogs
Step 3: Create a CNN to classify Dog Breeds (from Scratch)
Step 4: Use a CNN to classify Dog Breeds (using Transfer Learning)
Step 5: Create a CNN to classify Dog Breeds (using Transfer Learning)
Step 6: Write your Algorithm
Step 7: Test your Algorithm


### **Summary of the results**:

The model achieved a test accuracy of 80.98%, which is above the expected accuracy of 60%.
Our algorithm based on the Transfer Learning CNN was able to predict 3/4 dog breeds correctly, which is a very good result, 
considering that the CNN is able to distinguish between 133 dog breeds.
For the human faces, however, it has come to our attention that children's faces are not recognized as human faces,
which is a part of the algorithm that we could improve on.

### **Licensing, Authors, Acknowledgements**:
Must give credit to Udacity for the datasets and the underlying structure of the project.










