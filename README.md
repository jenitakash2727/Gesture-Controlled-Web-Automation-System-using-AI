# 🖐 Gesture-Controlled Web Automation System

## 📌 Overview
This project is an AI-based automation system that enables touchless control of web applications using real-time hand gesture recognition. It combines computer vision and browser automation to perform actions without physical interaction.

---

## 🚀 Features
- Real-time hand gesture detection using camera
- Gesture-based trigger for automation (open hand detection)
- Automated browser interaction using Selenium
- Dynamic web element handling (click, select, submit)
- End-to-end automation workflow

---

## 🧠 Technologies Used
- Python
- OpenCV
- MediaPipe
- Selenium
- Socket Programming

---

## ⚙️ How It Works
1. The system captures live video using a webcam.
2. MediaPipe detects hand landmarks and identifies gestures.
3. When an open-hand gesture is detected, automation is triggered.
4. Selenium opens a browser and interacts with web elements.
5. Actions like selecting options and submitting forms are performed automatically.

---

## 💡 Use Cases
- Touchless system control
- AI-based automation testing
- Accessibility solutions
- Smart UI interaction systems

---

## ▶️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/your-username/gesture-automation.git
cd gesture-automation
pip install opencv-python mediapipe selenium
python main.py
