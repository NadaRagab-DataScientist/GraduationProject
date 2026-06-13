# 🚗 Driver Drowsiness Detection System

## 📌 Overview
This project detects driver drowsiness in real-time using computer vision and machine learning.  
It identifies whether the driver's eyes are open or closed and triggers an alarm when drowsiness is detected.

---

## 🎯 Problem Statement
Driver fatigue is one of the major causes of road accidents.  
This system helps in early detection of drowsiness to improve road safety.

---

## 🧠 Approach
- Face detection using Haar Cascade
- Eye detection from ROI
- State classification: Open / Closed eyes
- Alarm triggered after consecutive closed frames

---

## 🛠️ Tech Stack
- Python
- OpenCV
- Haar Cascade Classifier
- Machine Learning (CNN optional version)
- Real-time Video Processing

---

## ⚙️ How It Works
1. Capture video from webcam
2. Detect face
3. Extract eye region
4. Check eye state (open/closed)
5. If closed for >12 frames → trigger alarm

---

## ▶️ Run Project
```bash
pip install -r requirements.txt
python app/main.py
