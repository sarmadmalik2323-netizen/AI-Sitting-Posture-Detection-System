# AI-Sitting-Posture-Detection-System
AI Sitting Posture Detection System analyzes images to classify posture as GOOD or BAD using YOLOv8 Pose Estimation and OpenCV. It detects keypoints, calculates spine angle, evaluates head alignment, and displays visual feedback. Works well in normal lighting, demonstrating practical AI and computer vision skills.
## Overview
This project is an AI-based **Sitting Posture Detection System** built using **Python, OpenCV, and YOLOv8 Pose Estimation**.  
It analyzes an uploaded image of a person sitting and predicts whether the posture is **GOOD** or **BAD** based on shoulder, hip, and head alignment.

The model does not have 100% accuracy, but it performs well in normal lighting and clear sitting positions.  
This project demonstrates practical skills in **Computer Vision, Pose Estimation, and Image Processing**.
This project is just for learning purpose but not for real time medical use.


## Features
- Detects a person in an uploaded image
- Extracts body keypoints using YOLOv8 Pose model
- Calculates spine angle using shoulder and hip centers
- Detects head forward position
- Classifies posture as **GOOD POSTURE** or **BAD POSTURE**
- Draws keypoints and spine line visually
- Displays posture benefits or possible risks
- Clean side-by-side visual output panel

## Technologies Used
- Python
- OpenCV
- NumPy
- Matplotlib
- Ultralytics YOLOv8 Pose


## How It Works
1. User uploads an image.
2. YOLOv8 detects human keypoints.
3. Shoulder center and hip center are calculated.
4. Spine angle is measured.
5. Head forward alignment is checked.
6. Posture is classified as Good or Bad.
7. Keypoints, spine line, and information panel are displayed.

## Author
**Muhammad Sarmad Mumtaz**  
BS Artificial Intelligence Student  

## Installation

### Install Dependencies
```bash
pip install ultralytics opencv-python matplotlib numpy

---


