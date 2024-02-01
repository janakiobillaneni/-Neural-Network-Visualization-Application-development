# COSC 6376 Cloud Computing Project
Testing a deployed computer vision model in a robust way can be challenging. The objective of this project is to create an application that users can deploy to visualize the output of their deployed computer vision model and gain insights and improve its performance. The application should enable users to store test images in a file system, which can be manually examined for correctness through a front-end UI. To support different models with varying input/output signatures, the application should be designed in a modular way (R1).

# Description of files 
 Above are the files we have created in this project.
 **model.h5** is the resnet model we have developed on Human Emotion Detection dataset from Kaggle. It is loaded in the **app.py** where we have our code using Flask for the web application.
 
 The .html files in **templates** folder are used to upload the image and display the output back to the user.
 
 **uploads** folder is the one where all the images uploaded by users are stored.
 
 We have other files (requirements.txt, runtime.txt, Procfile and Dockerfile) which are used for **runtime purpose** where we have specified all the required libraries for our project and the runtime environment versions.
 
 
 
 # Team Members:
 Susroonya Koduru (2141702) <br/>
 Varshitha Challa (2156555) <br/>
 Janaki Obillaneni (2149246) 
