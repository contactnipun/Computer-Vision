# Computer-Vision
Solving some common Computer Vision Problems

# Part 1
Domain: Entertainment

**Context** 
A company owns a movie application and repository which caters movie streaming to millions of users who on subscription basis. Company wants to automate the process of cast and crew information in each scene from a movie such that when a user pauses on the movie and clicks on cast information button, the app will show details of the actor in the scene. Company has an in-house computer vision and multimedia experts who need to detect faces from screen shots from the movie scene.

**Data Description**
The dataset comprises of images and its mask where there is a human face.

**Objective** 
Face detection from training images.

**Tasks**
1. Import the dataset.
2. Create features (images) and labels (mask) using that data.
3. Mask detection model:
  ● Design a face mask detection model.
  ● Design your own Dice Coefficient and Loss function.
  ● Train, tune and test the model.
  ● Evaluate the model using testing data.
4. Using a Test imageas an input to the designed model and displaying the output of the image.

Acknowledgement for the dataset http://mmlab.ie.cuhk.edu.hk/projects/WIDERFace/
Mobile Net paper: https://arxiv.org/pdf/1704.04861.pdf


# Part 2

• DOMAIN: Entertainment
• CONTEXT: Company X owns a movie application and repository which caters movie streaming to millions of users who on subscription
basis. Company wants to automate the process of cast and crew information in each scene from a movie such that when a user pauses on
the movie and clicks on cast information button, the app will show details of the actor in the scene. Company has an in-house computer
vision and multimedia experts who need to detect faces from screen shots from the movie scene.
• TASK: Help to create an image dataset to be used by the AI team to build an image classifier data. Profile images of people are given.
1. You are expected to curate the bounding box co-ordinates for each image. These are also called annotations.
2. This task can be done using manual methods where you need to open each image and note the coordinates where the face located
[though it is not recommended]. This task can be easily done using an automation where you need to input the image in the
automation and the output is the coordinates of the face detected from the image. [this is highly recommended]. Also highlight how
many faces detected in each image.
Refer to the sample image below:
3. Comment on the challenges faced during this task.
Please note: This will require your analytical, research and development skills to try and design the automation required.
Acknowledgement for the dataset: https://www.kaggle.com/ciplab/real-and-fake-face-detection

# Part 3

DOMAIN: Face recognition
• CONTEXT: Company X intends to build a face identification model to recognise human faces.
• DATA DESCRIPTION: The dataset comprises of images and its mask where there is a human face.
• PROJECT OBJECTIVE: Face Aligned Face Dataset from Pinterest. This dataset contains 10,770 images for 100 people. All images are taken
from 'Pinterest' and aligned using dlib library. 

 TASK: In this problem, we use a pre-trained model trained on Face recognition to recognise similar faces. Here, we are particularly
interested in recognising whether two given faces are of the same person or not. Below are the steps involved in the project.
• Load the dataset and create the metadata.
• Check some samples of metadata.
• Load the pre-trained model and weights.
• Generate Embedding vectors for each face in the dataset.
• Build distance metrics for identifying the distance between two given images.
• Use PCA for dimensionality reduction.
• Build an SVM classifier to map each image to its right person.
• Predict using the SVM model.


# Part 4

• DOMAIN: State traffic department
• CONTEXT: City X’s traffic department wants to understand the traffic density on road during busy hours in order to efficiently program
their traffic lights.
• TASK: Create an automation using computer vision to impute dynamic bounding boxes to locate cars or vehicles on the road. It would
require for you to do some research on how to impute bounding boxes on video file. You can use video provided with this assignment or
any video of your choice which has moving cars to impute bounding boxes.


