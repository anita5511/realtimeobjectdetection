# Real-Time Object Detection with YOLO

## 📖 Description
This repository demonstrates how to perform real-time object detection on images and videos using the Ultralytics YOLO model and OpenCV. It includes utilities for:

- Detecting and displaying annotated bounding boxes on still images
- Processing video files frame by frame, annotating detections, and saving the result
- (Optional) Mounting Google Drive in Colab to load/store data

---

## Features

- **Image Detection**: Run inference on a single image and visualize/save the annotated result.
- **Video Detection**: Read an input video, perform frame-by-frame detection, and write an annotated video.
- **Easy Setup**: One-line pip install for dependencies.
- **Google Colab Compatible**: Helper to mount Google Drive.

---

## Requirements

- Python 3.7 or higher  
- `opencv-python`  
- `ultralytics` (YOLO)  
- `matplotlib`

---

## Installation

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/realtime_objectdetect_video.git
   cd realtime_objectdetect_video
   ```
2. Install dependencies:
   ```bash
   pip install opencv-python ultralytics matplotlib
   ```
3. Download or train a YOLO model (e.g., `yolo12n.pt`) and place it at the repo root.
