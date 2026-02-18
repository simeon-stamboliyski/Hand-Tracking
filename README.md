# ✋ Hand Tracking Computer Vision App

Real-time hand tracking application built with **OpenCV** and **MediaPipe**.

This project uses your webcam to detect and track hand landmarks in real time.  
It draws **21 hand keypoints** and the connections between them directly on the video stream.

---

## 🚀 Features

- Real-time webcam capture  
- Hand landmark detection (21 keypoints)  
- MediaPipe Hands model integration  
- Smooth tracking with adjustable confidence  
- Press `ESC` to exit the application  

---

## 🛠 Technologies Used

- Python  
- OpenCV  
- MediaPipe  

---

## 📦 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/Sava-Statkov/Hand-Tracking.git
cd Hand-Tracking
RUN THE APPLICATION
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python hand_tracking.py
Troubleshooting
If your camera does not open, try changing:

cv2.VideoCapture(0) to:
cv2.VideoCapture(1)
