# Computer-Vision
Solving some common Computer Vision Problems

# Part 1
**Domain**: Entertainment

**Context** 
A company owns a movie application and repository which caters movie streaming to millions of users who on subscription basis. Company wants to automate the process of cast and crew information in each scene from a movie such that when a user pauses on the movie and clicks on cast information button, the app will show details of the actor in the scene. Company has an in-house computer vision and multimedia experts who need to detect faces from screen shots from the movie scene.

**Data Description**
The dataset comprises of images and its mask where there is a human face.

**Objective** 
Face detection from training images.

**Tasks**
   1. Importing the dataset.
    
   2. Creating features (images) and labels (mask) using that data.
    
   3. Masking detection model:

            ● Designing a face mask detection model.

            ● Designing Dice Coefficient and Loss function.

            ● Training, tuning and testing the model.

            ● Evaluating the model using testing data.

  4. Using a Test image as an input to the designed model and displaying the output of the image.


Acknowledgement for the dataset http://mmlab.ie.cuhk.edu.hk/projects/WIDERFace/

Mobile Net paper: https://arxiv.org/pdf/1704.04861.pdf


# Part 2

**Domain**: Entertainment

**Context**: A Company owns a movie application and repository which caters movie streaming to millions of users who on subscription basis. Company wants to automate the process of cast and crew information in each scene from a movie such that when a user pauses on the movie and clicks on cast information button, the app will show details of the actor in the scene. Company has an in-house computer vision and multimedia experts who need to detect faces from screen shots from the movie scene.

**Tasks**: Creating an image dataset to be used by the AI team to build an image classifier data. Profile images of people are given in the raw data.

1. Curating the bounding box co-ordinates for each image. These are also called annotations.

2. This task can be done using manual methods where you need to open each image and note the coordinates where the face located [though it is not recommended]. 
      This task can be easily done using an automation where we need to input the image in the automation and the output is the coordinates of the face detected from the image. [this is highly recommended]. Highlighting how many faces are detected in each image.


Acknowledgement for the dataset: https://www.kaggle.com/ciplab/real-and-fake-face-detection

# Part 3
**Domain**: Face recognition

**Context**
A Company intends to build a face identification model to recognise human faces.

**Data Description** 
The dataset comprises of images and its mask where there is a human face. This dataset contains 10,770 images for 100 people. All images are taken from 'Pinterest' and aligned using dlib library. 

**Objective**
Face Aligned Face Dataset from Pinterest. 

 **Task**: In this problem, we use a pre-trained model trained on Face recognition to recognise similar faces. Here, we are particularly interested in recognising whether two given faces are of the same person or not. Below are the steps involved in the project.
 
      • Loading the dataset and create the metadata.
      • Checking some samples of metadata.
      • Loading the pre-trained model and weights.
      • Generating Embedding vectors for each face in the dataset.
      • Building distance metrics for identifying the distance between two given images.
      • Using PCA for dimensionality reduction.
      • Building an SVM classifier to map each image to its right person.
      • Predicting using the SVM model.


# Part 4

**Domain**: State traffic department

**Context**: City X’s traffic department wants to understand the traffic density on road during busy hours in order to efficiently program their traffic lights.

**Tasks**: Create an automation using computer vision to impute dynamic bounding boxes to locate cars or vehicles on the road. It equires some research on how to impute bounding boxes on video file.


