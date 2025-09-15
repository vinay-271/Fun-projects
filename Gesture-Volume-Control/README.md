# 🎛️ Gesture Volume Control  

A fun project where you can **control system volume with hand gestures** 🎶.  
If you pinch (thumb + index finger close), the volume lowers, and if you separate them, the volume increases.  
It’s not super smooth, but it was a great exercise in using computer vision and audio libraries.  

---

## ✨ Features
- Detects hand landmarks using **Mediapipe**
- Tracks distance between thumb and index finger
- Maps distance to **system volume level** using Pycaw
- Simple and fun experiment with gesture-based controls

---

## 🛠️ Tech Stack & Libraries
- [OpenCV](https://opencv.org/) – Computer vision  
- [Mediapipe](https://developers.google.com/mediapipe) – Hand tracking  
- [PyCaw](https://github.com/AndreMiras/pycaw) – Windows audio control  
- [NumPy](https://numpy.org/) – Math operations  
- Python standard libraries: `math`, `time`, etc.

---

## 📦 Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/your-username/MyProjects.git
cd GestureVolumeControl
pip install opencv-python mediapipe pycaw numpy