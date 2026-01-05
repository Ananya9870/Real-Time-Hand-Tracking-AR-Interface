# Real-Time-Hand-Tracking-AR-Interface

A real-time **hand tracking augmented reality (AR) interface** that overlays a futuristic HUD directly on the user’s palm using **OpenCV** and **MediaPipe**. The system detects hand gestures and dynamically renders holographic UI elements that respond to finger movements.

---

## 🚀 Features

* Real-time hand detection and tracking using MediaPipe Hands
* Gesture recognition (Open hand, Pinch, Fist)
* Futuristic AR HUD overlay anchored to the palm
* Dynamic UI elements:

  * Glowing circular rings
  * Radial ticks and arc segments
  * Core animated patterns
  * Finger-to-palm connectors
  * Angle measurement between fingers
* Smooth glow effects and sci-fi visual design

---

## 🧠 Core Concepts Used

* Computer Vision (OpenCV)
* Hand Pose Estimation (MediaPipe)
* Gesture Recognition
* Vector Mathematics (distance & angle calculations)
* Augmented Reality UI overlays
* Human–Computer Interaction (HCI)

---

## ✋ Supported Gestures

| Gesture     | Description                  | UI Response                 |
| ----------- | ---------------------------- | --------------------------- |
| Open Hand ✋ | Fingers spread               | Full AR HUD interface       |
| Pinch 🤏    | Thumb and index finger close | Orange arc UI + pinch value |
| Fist ✊      | Fingers closed               | Simple glowing indicator    |

---

## 🛠 Tech Stack

* **Language:** Python
* **Libraries:**

  * OpenCV
  * MediaPipe
  * NumPy

---

## ⚙️ Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/Real-Time-Hand-Tracking-AR-Interface.git
cd Real-Time-Hand-Tracking-AR-Interface
```

2. Install dependencies

```bash
pip install opencv-python mediapipe numpy
```

3. Run the project

```bash
python main.py
```

> Make sure your webcam is connected and accessible.

---

## 📄 License

This project is licensed under the MIT License – feel free to use, modify, and distribute.
