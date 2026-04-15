# Vehicle Counting with YOLO + DeepSORT
A simple vehicle detection, tracking, and counting system using YOLO and DeepSORT.

## Overview
This project implements a **vehicle detection, tracking, and counting system** using:

- **YOLO** for object detection  
- **DeepSORT** for multi-object tracking  

The system detects vehicles in a video, assigns unique IDs, tracks them across frames, and counts vehicles when they cross a predefined line.

---

## Features
- Real-time vehicle detection (car, truck, bus, etc.)
- Unique ID tracking using DeepSORT
- Line-crossing based counting
- Output video with:
  - Bounding boxes
  - Track IDs
  - Total count

---

## Requirements

- Python >= 3.8  
- torch  
- opencv-python  
- numpy  
- ultralytics  

---

## How to run 
1. Set the input video path and output video path in the code.
2. Run the script.

---
This project is for educational purposes only.
