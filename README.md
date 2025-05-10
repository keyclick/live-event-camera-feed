## Live Event Camera Feed with Real-Time Pose Detection

This project captures and visualizes real-time data from an event-based camera using the `dv-processing` SDK. It integrates TensorFlow MoveNet to perform human pose estimation, overlaying pose keypoints as the data streams live. Originally developed to assist in analyzing **human gait and posture**, the system was designed to capture anchor points of patients in real-time—enabling early detection of abnormalities such as gait instability, changes in walking patterns, or postural issues. The captured data can later be processed into formats like MP4 or JPEG using publicly available libraries for further analysis or reporting.


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
