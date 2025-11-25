## Instagram Filter – Blemish Removal & Chroma Keying

# 📌 Overview
This project is an AI-based Computer Vision application that mimics an Instagram-style beauty filter. It performs blemish removal / skin smoothing and chroma keying (background replacement) on an input image using classical image-processing techniques. The objective is to build an image-processing pipeline using OpenCV that enhances facial features and replaces the background with a custom image.

## 📌 Problem Statement
Modern social media platforms offer filters that smooth skin, reduce blemishes, and change backgrounds.
This project aims to replicate these effects offline using Python and OpenCV:
  1. Detect the face region and apply smoothing to reduce blemishes or skin imperfections.
  2. Identify a green/solid background using chroma keying and replace it with a custom background.

## 📌 Data Preprocessing & Feature Engineering
### 1. Face Detection
  * Using Haar Cascade / Dlib / MediaPipe to detect facial landmarks or bounding box.
### 2. Skin Smoothing / Blemish Removal
  * Applied filters:
    * Bilateral Filter
    * Gaussian / Median Smoothing
    * OpenCV Inpainting for removing specific blemishes
### 3. Chroma Keying
  * Convert image to HSV color space
  * Create a mask for background (e.g., green-screen detection)
  * Apply bitwise operations to merge with a new background

### 4. Final Image Composition
  * Combine smoothed face + replaced background to generate the final output.

## 📌 Model Used
This project does not use deep learning.It uses classical Computer Vision methods:
  * Haar Cascade Classifier (Face Detection)
  * OpenCV Filters & Inpainting
  * HSV Masking for Chroma Keying
  * Bitwise operations for background replacement

## 📌 Model Evaluation Metrics
  * Evaluation is done visually based on:
    * Accuracy of face detection
    * Smoothness of skin without distortion
    * Quality of background masking
    * Clean boundary between foreground and background
   
## 📌 Model Performance
  * Executes in real-time on static images.
  * Skin smoothing maintains detail while reducing noise.
  * Chroma keying works well on uniform backgrounds (especially green).
  * Clean output with stable blending of foreground & new background

## 📌 Technologies Used
  * Python 3
  * OpenCV
  * NumPy
  * Mediapipe / Dlib 
  * Jupyter Notebook / Google Colab

## 📌 Uses 
  * Can be used to build beauty filters similar to Instagram/Snapchat.
  * Useful for background removal in photography and videography.
  * Helps understand fundamental image processing and computer vision concepts.
