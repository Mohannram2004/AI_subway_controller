# 🎮 AI-Powered Gesture-Based Subway Surfer Controller for Hand-Disabled Players

---

## 📜 Project Description

This project is a **gesture-based AI controller** built using **OpenCV**, **MediaPipe**, and **PyAutoGUI** that allows **individuals with hand disabilities** to play **Subway Surfer** (or similar online games) using only **head movements** detected through a webcam.

The controller divides the camera frame into four zones:

- ➡️ Move head **right** → triggers **Right Arrow** key  
- ⬅️ Move head **left** → triggers **Left Arrow** key  
- ⬆️ Move head **up** → triggers **Up Arrow** key (Jump)  
- ⬇️ Move head **down** → triggers **Down Arrow** key (Slide)  

This solution provides a **hands-free, inclusive gaming experience** with **no extra hardware** — just a webcam and Python.

---

## ✨ Features

- 🎥 Real-time head gesture tracking using **MediaPipe**
- 🧠 Smart screen division logic with zone-based detection
- 🕹️ Simulates keyboard keypresses via **PyAutoGUI**
- ⚡ Minimal latency, fast response
- ♿ Specially designed for **accessibility**
- ✅ Works on any standard PC with webcam

---

## 📦 Technologies Used

| Technology   | Purpose                                 |
|--------------|------------------------------------------|
| Python 3     | Programming language                     |
| OpenCV       | Webcam input & image processing          |
| MediaPipe    | Face/landmark tracking                   |
| PyAutoGUI    | Automate keypresses based on gestures    |

---

## 🖥️ How It Works

1. The webcam captures your face/head in real-time.  
2. MediaPipe detects head position landmarks.  
3. The screen is divided into 4 control zones (left, right, up, down).  
4. Based on the head movement, corresponding key presses are triggered.  
5. You can play the game without using hands or external devices.

---

## 🛠️ Setup Instructions

### 🔧 Prerequisites

- Python 3.x installed  
- A working webcam  

---

### 📥 Installation

1. **Clone this repository**

```bash
git clone https://github.com/Mohannram2004/AI_subway_controller.git
cd AI_subway_controller



