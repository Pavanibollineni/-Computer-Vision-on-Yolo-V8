# Computer Vision using YOLOv8 and StrongSORT

## 📌 Overview
This project demonstrates multi-object detection and tracking using YOLOv8 and StrongSORT. YOLOv8 is used for detecting objects in each frame, while StrongSORT is used to track those objects across frames by assigning unique IDs.

---

## ⚙️ Technologies Used
- Python
- YOLOv8 (Ultralytics)
- StrongSORT (BoxMOT)
- OpenCV
- Google Colab (T4 GPU)

---

## 🚀 Implementation Steps

### 1. Setup Environment
- Installed required libraries using pip
- Used Google Colab with GPU support

### 2. Object Detection
- Loaded YOLOv8 model (`yolov8n.pt`)
- Detected objects frame-by-frame

### 3. Object Tracking
- Used StrongSORT algorithm
- Assigned unique IDs to detected objects
- Maintained identity across frames

---

## 📂 Input
- Custom video (`moving.mp4`)

---

## 📊 Output
- Video with:
  - Bounding boxes around objects
  - Unique tracking IDs (ID 1, ID 2, etc.)

---

## 🧠 StrongSORT Explanation
StrongSORT is an advanced multi-object tracking algorithm that improves tracking accuracy by combining motion prediction and appearance-based feature matching. It uses a Kalman filter to predict object movement and deep learning-based features to maintain identity across frames. It also handles occlusions and missed detections effectively.

---

## 📌 Observations
- Objects were successfully detected and tracked
- Each object was assigned a consistent ID
- Tracking remained stable even when objects moved

---

## ✅ Conclusion
The combination of YOLOv8 and StrongSORT provides an efficient solution for real-time object detection and tracking. This approach can be applied in surveillance, traffic monitoring, and video analysis systems.

---
