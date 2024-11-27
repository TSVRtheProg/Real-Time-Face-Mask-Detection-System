# Video-Based Real-Time Face Mask Detection System 😷

## Project Overview 🌟

This project is to develop a real-time face mask detection system utilizing deep learning and computer vision techniques. The system was developed to determine whether or not a person is wearing a face mask from video streams in real time. It accomplishes this operation using a pre-trained MobileNetV2 model and OpenCV.

## Contents 📚
  - **Project Goals 🎯**
    
  - **Datasets Used 📊**
    
  - **Steps to Perform**
    
  - **Conclusion 🏁**

## Project Goals 🎯

The major goal of this project is to automate the process of monitoring face mask compliance by utilizing the latest methods in machine learning. The method can be used to ensure compliance with health guidelines in a variety of situations, including workplaces, public transportation, and other public locations.

## Datasets Used 📊

The dataset consists of images categorized into two classes: "with_mask" and "without_mask". The images were preprocessed to a target size of 224x224 pixels before being fed into the model.

# Face Mask Detection Project

## Steps to Perform

### 1. Installation 🛠️
To get started with this project, we installed the necessary dependencies:
- `imutils`
- `opencv-python`
- `tensorflow`

### 2. Model Training 🧠
The face mask detection model was built using the MobileNetV2 architecture, which is a lightweight and efficient convolutional neural network. The model was fine-tuned on our dataset to classify images into the two categories.

**Key Steps in Model Training:**

1. **Data Preprocessing:**
    - Loaded and preprocessed images.
    - Converted images to arrays and normalized pixel values.

2. **Data Augmentation:**
    - Applied various transformations to augment the dataset and improve model generalization.

3. **Model Architecture:**
    - Used MobileNetV2 as the base model.
    - Added custom layers on top for classification.

4. **Compilation and Training:**
    - Compiled the model with the Adam optimizer.
    - Trained the model on the dataset.

The model achieved high accuracy in both training and validation phases, demonstrating its effectiveness in distinguishing between images with and without masks.

### 3. Real-Time Detection 🎥
The real-time face mask detection system was implemented using OpenCV to capture video frames from a webcam and process each frame to detect faces and determine if they are wearing masks.

**Key Steps in Real-Time Detection:**

1. **Load Pre-trained Models:**
    - Loaded the face detector model.
    - Loaded the mask detector model.

2. **Video Stream Processing:**
    - Captured frames from the webcam.
    - Detected faces in each frame.
    - Predicted mask status for each detected face.
    - Displayed the results with bounding boxes and labels.

The system was tested in real-time  and was able to accurately detect face masks.


## Conclusion 🏁

The face mask detection system obtained good accuracy during both the training and validation stages. It can detect face masks in real time, making it a useful solution for checking compliance with health rules. The project highlights the effectiveness of integrating deep learning with computer vision to solve problems in the real world.

---

## **_Data science is like a puzzle – sometimes the pieces don't fit, but with enough coffee and Google searches, they magically do!_** 😄☕
