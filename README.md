# opencv-camera-processing

# Overview

This project demonstrates image capture and video processing using OpenCV in Python. The webcam is used to capture images and process live video frames with different operations such as resizing and rotation.

The experiment uses OpenCV and Matplotlib for capturing, processing, and displaying video frames.

---

# Objectives

- Capture an image using webcam
- Display captured image using Matplotlib
- Read and display live video frames
- Resize video frames
- Rotate video frames
- Understand basic video processing techniques using OpenCV

---

# Software Required

- Python
- OpenCV
- Matplotlib
- IPython

---

# Theory

## OpenCV

OpenCV (Open Source Computer Vision Library) is a powerful library used for image processing, computer vision, and video analysis applications.

---

## Image Capture

The webcam is accessed using:

```python
cv2.VideoCapture(0)
```

A single frame is captured and saved as an image.

---

## Video Processing

Video processing involves reading frames continuously from the webcam and applying operations such as:

- Displaying video frames
- Resizing frames
- Rotating frames

---

# Algorithm

## Image Capture

1. Import required libraries
2. Access webcam using OpenCV
3. Capture a single frame
4. Save the captured image
5. Display the image using Matplotlib

---

## Video Display

1. Access webcam
2. Read video frames continuously
3. Convert BGR image to RGB
4. Display frames using Matplotlib

---

## Video Resizing

1. Read frames from webcam
2. Resize frames using `cv2.resize()`
3. Display resized video frames

---

## Video Rotation

1. Read frames from webcam
2. Rotate frames using `cv2.rotate()`
3. Display rotated video frames

---


---

# Output

## Image Capture
- Captured image from webcam displayed successfully

## Video Processing
- Live webcam video displayed
- Resized video frames displayed
- Rotated video frames displayed

---

# Result

Thus, image capture and video processing operations such as displaying, resizing, and rotating video frames were successfully performed using OpenCV in Python.

---
