# Live Event Camera Feed with Real-Time Pose Detection

This project captures and visualizes real-time data from an **event-based camera** using the `dv-processing` SDK. It also applies human pose estimation via **TensorFlow MoveNet**, overlaying pose keypoints live as the data streams in. The captured anchor points can be stored for further processing and converted into standard formats such as MP4 or JPEG using publicly available tools.

---

## 🎯 Project Purpose

This project was developed to demonstrate:
- Real-time integration with an event-based camera
- Event data processing and accumulation
- Live pose detection using a lightweight deep learning model (MoveNet)
- Real-time visualization and data readiness for post-processing

This project is intended for inclusion in a professional CV/portfolio to showcase computer vision, deep learning, and camera integration skills.

---

## 🖥️ Features

- ✅ Connects to an event-based camera
- ✅ Streams and accumulates events in real-time
- ✅ Applies **MoveNet** pose detection (TensorFlow Lite model)
- ✅ Draws pose keypoints and skeleton live on frame
- ✅ Outputs can be saved locally for further processing (e.g., MP4/JPEG/export via OpenCV)

---

## 🚀 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/live-event-camera-feed.git
cd live-event-camera-feed
