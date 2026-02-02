# Signature-based-pose-detection-authentication-system
Signature-Based Pose Detection Authentication System using Computer Vision and Machine Learning for secure user authentication based on human body pose patterns

## Overview
This project implements a signature-based authentication system using human pose detection. 
Instead of traditional passwords, users are authenticated based on unique body pose patterns 
captured through a camera, making the system more secure and difficult to spoof.

## Key Features
- Pose-based user authentication
- Signature pattern matching using pose landmarks
- Real-time pose detection
- Improved security compared to password-based systems

## Technologies Used
- Python
- MediaPipe Pose
- OpenCV
- NumPy
- FastAPI (Backend API)
- HTML, CSS (Frontend)

## How It Works
1. The system captures the user's pose using a camera.
2. Pose landmarks are extracted using MediaPipe.
3. The extracted pose signature is stored during registration.
4. During login, the current pose is compared with the stored signature.
5. Authentication is granted if the similarity score is above a threshold.

## Group Project
This project was developed as a **group project** as part of academic coursework.

### Team Members
- Shrishti Gautam
-Anubhav Pandey


This repository is my personal copy of the group project created for learning, demonstration, and placement purposes.
