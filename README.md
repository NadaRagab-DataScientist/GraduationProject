# 🚗 Real-Time Driver Drowsiness Detection System

## 📌 Overview
This project is a real-time Driver Drowsiness Detection system using Computer Vision techniques.  
It monitors the driver's eyes through a webcam and detects signs of fatigue. If drowsiness is detected, an alarm is triggered immediately to enhance road safety.

The system simulates a real-time binary classification problem (Eye Open vs Closed) combined with temporal sequence analysis for fatigue detection.

---

## 🎯 Problem Statement
Driver fatigue is one of the leading causes of road accidents worldwide.  
This system aims to detect early signs of drowsiness using real-time video analysis and prevent potential accidents by triggering an alert when fatigue is detected.

---

## 🧠 Approach
The system follows a real-time computer vision pipeline:

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
- Computer Vision Pipelines  

---

## 🚨 Alert Mechanism
If the eyes remain closed for more than a defined threshold of consecutive frames,  
the system triggers an audible alarm to alert the driver in real-time.



---

## 🚀 Future Improvements
- Replace Haar Cascade with a Deep Learning-based CNN model  
- Improve robustness under low-light and noisy environments  
- Add yawning detection for better fatigue analysis  
- Deploy as a mobile or embedded system (Raspberry Pi / Edge AI)

---

## 👩‍💻 Author
**Nada Ragab**  
Data Scientist | Machine Learning & Computer Vision Engineer  

---

## 📜 License
This project is licensed under the MIT License.
