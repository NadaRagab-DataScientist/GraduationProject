# 🚗 Driver Drowsiness Detection System

## 📌 Overview
A real-time Driver Drowsiness Detection system using Computer Vision and Machine Learning.  
The system monitors the driver’s eyes through webcam input and detects signs of fatigue. If drowsiness is detected, an alarm is triggered immediately to enhance road safety.

---

## 🎯 Problem Statement
Driver fatigue is one of the leading causes of road accidents worldwide.  
This project aims to build an intelligent system that detects early signs of drowsiness and prevents potential accidents.

---

## 🧠 Approach
The system follows a real-time pipeline:

- Face detection using Haar Cascade Classifier  
- Eye Region of Interest (ROI) extraction  
- Eye state classification (Open / Closed)  
- Temporal logic: consecutive closed frames tracking  
- Alarm activation if eyes remain closed for > 12 frames  

---

## 🛠️ Tech Stack
- Python  
- OpenCV  
- Haar Cascade Classifier  
- NumPy  
- Real-time Video Processing  

---

## ⚙️ System Workflow
1. Capture video stream from webcam  
2. Detect face in each frame  
3. Extract eye region (ROI)  
4. Classify eye state (Open / Closed)  
5. Count consecutive closed frames  
6. Trigger alarm when threshold is exceeded  

---

## 📁 Project Structure
