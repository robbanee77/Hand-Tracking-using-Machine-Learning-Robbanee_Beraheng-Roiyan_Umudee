# Introduction
It is an application of computer vision, object detection in various key positions of the hand to detect and track the position and gesture of the hand. This is the same way that Face Mesh works or a program used to detect and track faces.
# Project Prerequisites:
You need to install the dlib library and face_recognition API from PyPI:
- pip install opencv-python
- pip install mediapipe
# Steps to implement Face Recognition
We will build this python project in two parts. We will build two different python files for these two parts:
- embedding.py:

First, create a file embedding.py in your working directory. In this file, we will create face embeddings of a particular human face. We make face embeddings using face_recognition.face_encodings method. These face embeddings are a 128 dimensional vector. In this vector space, different vectors of same person images are near to each other. After making face embedding, we will store them in a pickle file.

-  recognition.py:

Here we will again create person’s embeddings from the camera frame. Then, we will match the new embeddings with stored embeddings from the pickle file. The new embeddings of same person will be close to its embeddings into the vector space. And hence we will be able to recognize the person.

# Requirements :
Jupyter Notebook
# Importing the Libraries :
- mediapipe as mp
- cv2


# CONCLUSION
This deep learning project teaches you how to develop a human face recognition project with python libraries dlib and face_recognition APIs (of OpenCV).

It also covers the introduction to face_recognition API. We have implemented this python project in two parts:

In the first part, we have seen how to store the information about human face structure, i.e face embedding. Then we learn how to store these embeddings.
In the second part, we have seen how to recognize the person by comparing the new face embeddings with the stored one.





