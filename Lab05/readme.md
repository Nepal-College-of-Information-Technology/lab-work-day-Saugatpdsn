# MMS Lab 5  
## Image Classification Using OpenCV and Pre-trained Deep Learning Model

---

##  Title
*Image Classification using OpenCV and Pre-trained Deep Learning Model*

---

## Objectives
The main objectives of this lab are:

1. To find and use a pre-trained Convolutional Neural Network (CNN) model for gender classification.
2. To load the pre-trained deep learning model and test images using OpenCV.
3. To detect the Region of Interest (ROI), specifically the face region, and classify the test image.

---

##  Background Theory

### 1. Image Detection and Recognition
Image detection involves locating objects or regions of interest (such as faces) within an image, while image recognition focuses on identifying or classifying those detected objects. In this lab, face detection is performed before classification.

### 2. Image Processing Using OpenCV in Python
OpenCV is an open-source computer vision library widely used for image processing tasks such as image loading, resizing, face detection, and visualization. Python bindings of OpenCV make it easy to integrate with deep learning models.

### 3. Classical Machine Learning vs Deep Learning
Classical machine learning methods rely on manual feature extraction, whereas deep learning automatically learns features from raw data. CNNs, a type of deep learning model, are especially effective for image-based tasks.

### 4. Convolutional Neural Network (CNN)
A CNN is a deep learning architecture designed for image analysis. It uses convolutional layers to extract features such as edges, textures, and shapes, followed by fully connected layers for classification. Pre-trained CNN models can be reused for tasks like gender classification.

---

## 🛠 Tools and Technologies Used
- Python  
- OpenCV  
- Pre-trained CNN model  
- NumPy  

---

##  Methodology
1. Load the pre-trained CNN model.
2. Read the input image using OpenCV.
3. Detect the face region (ROI) from the image.
4. Resize and preprocess the ROI as required by the model.
5. Classify the image using the pre-trained model.
6. Display the classification result.

---

## Outcome
The system successfully detects the face region from the input image and classifies the gender using a pre-trained deep learning model, demonstrating the effectiveness of CNN-based image classification.

---

##  Conclusion
This lab demonstrates how OpenCV and pre-trained deep learning models can be combined to perform image classification tasks efficiently. Using CNNs significantly improves accuracy compared to traditional machine learning approaches.