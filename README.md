# Road-Damage-Detection-System

### Project Overview
This project implements a computer vision system that detects and classifies road damage (such as potholes and cracks) using the YOLO (You Only Look Once) object detection model. The system includes a user-friendly web interface built with Gradio for easy interaction.

### Features
-Real-time detection of road damage in images 
-Classification of damage types (potholes, cracks)
-Severity assessment based on confidence scores
-Color-coded bounding boxes indicating damage severity
-Interactive web interface for uploading and analyzing images

### Technologies Used
-Python
-YOLO (YOLOv8) for object detection
-OpenCV for image processing and visualization
-Gradio for creating the interactive web interface
-PIL (Python Imaging Library) for image handling
-NumPy for numerical operations

### Project Structure
The project is organized as a Jupyter notebook with the following components:
1.Setup and Dependencies: Installation of required libraries

2.Model Loading: Loading the pre-trained YOLO model for road damage detection

3.Visualization Functions:
-Drawing bounding boxes with color coding based on damage type and severity
-Generating detailed damage reports

4.Prediction Function: Processing images and detecting road damage

5.Gradio Interface: Creating an interactive web application for easy usage

### Model Details
The system uses a YOLOv8 model trained on the Road Damage Detector dataset. The model can detect different types of road damage with the following severity indicators:
-Red boxes: High-confidence pothole detection (severe damage)
-Orange boxes: Medium-confidence pothole detection (moderate damage)
-Yellow boxes: Low-confidence pothole detection or other damage types (minor damage)

