# 🚗 Real-Time Driver Drowsiness Detection System

## 📌 Overview
This project is a real-time Driver Drowsiness Detection system using Computer Vision techniques.  
It monitors the driver's eyes through a webcam and detects signs of fatigue. If drowsiness is detected, an alarm is triggered immediately to enhance road safety.

---

## 🎯 Problem Statement
Driver fatigue is one of the leading causes of road accidents worldwide.  
This system aims to detect early signs of drowsiness using real-time video analysis and prevent potential accidents by triggering an alert when fatigue is detected.

---

## 🧠 Approach
The system follows a real-time processing pipeline:

- Face detection using Haar Cascade Classifier  
- Eye Region of Interest (ROI) extraction  
- Eye state detection (Open / Closed)  
- Temporal logic based on consecutive closed frames  
- Alarm activation when threshold is exceeded  

---

## ⚙️ System Workflow
1. Capture video stream from webcam  
2. Detect face in each frame  
3. Extract eye region (ROI)  
4. Classify eye state (Open / Closed)  
5. Count consecutive closed frames  
6. Trigger alarm when drowsiness is detected  

---

## 🛠️ Tech Stack
- Python  
- OpenCV  
- NumPy  
- Haar Cascade Classifier  
- Real-time Video Processing  

---

## 🚨 Alert Mechanism
If the eyes remain closed for more than a defined number of consecutive frames,  
the system triggers an audio alarm to alert the driver immediately.

---

## 📁 Project Structure
Driver-Drowsiness-Detection/
│
├── Detection/
│   ├── face_detection.py
│   ├── eye_detection.py
│
├── Classification/
│   ├── model.py
│
├── cascades/
│   ├── haarcascade_eye.xml
│   ├── haarcascade_frontalface.xml
│
├── assets/
│   ├── alarm.mp3
│
├── main.py
├── requirements.txt
└── README.md
---

## 🚀 Future Improvements
- Replace Haar Cascade with Deep Learning model (CNN)  
- Improve accuracy under low-light conditions  
- Add yawning detection  
- Deploy as mobile or embedded system  

---

## 👩‍💻 Author
**Nada Ragab**  
Data Scientist | AI & Machine Learning Enthusiast  

---

## 📜 License
This project is licensed under the MIT License.
