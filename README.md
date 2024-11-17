# Age and Gender Detection  

This project implements a **deep learning-based system** to detect a person's age and gender from facial images or video streams. It uses **pre-trained DNN models** and OpenCV for efficient face detection and classification. The system is designed for real-time applications with accurate predictions.  

## Features  
- **Age Detection**: Predicts approximate age groups such as `(0-2)`, `(25-32)`, `(60-100)`, and more.  
- **Gender Detection**: Classifies gender as **Male** or **Female**.  
- **Real-Time Support**: Works seamlessly with images, video files, or live webcam feeds.  
- **Lightweight and Fast**: Uses optimized pre-trained models for quick processing.  

## Technology Stack  
- **Deep Learning Models**: Pre-trained DNN models using the Caffe framework.  
- **Library**: OpenCV's DNN module for face detection and inference.  
- **Languages**: Python for seamless integration and flexibility.  

## How It Works  
1. Detects faces in the input image or video using OpenCV.  
2. Extracts and preprocesses the face region for model compatibility.  
3. Feeds the processed face into pre-trained models to classify **age** and **gender**.  
4. Displays the results with bounding boxes and labels on the output.  


