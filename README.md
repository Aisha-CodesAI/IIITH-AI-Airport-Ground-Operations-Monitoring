# IIITH-AI-Airport-Ground-Operations-Monitoring
Summer Internship project i-hub IIITH

# AI-Based Airport Ground Operations Monitoring System

## Overview
This project is an AI-powered Airport Ground Operations Monitoring System developed using YOLO Object Detection. The system detects and monitors airport operational objects such as airport vehicles, baggage carts, containers, and airplanes from airport surveillance videos.

The model was custom trained using annotated airport datasets extracted from raw surveillance footage. The project demonstrates real-time AI-based object detection for improving airport safety and operational monitoring.

---

# Features

- Real-time airport object detection
- Custom-trained YOLO model
- Airport vehicle monitoring
- Baggage cart detection
- Container detection
- Airplane detection
- Video-based AI surveillance
- Automated airport monitoring system
- Custom dataset training

---

# Technologies Used

- Python
- YOLOv11 / Ultralytics YOLO
- OpenCV
- NumPy
- FFmpeg
- VS Code

---

# Project Structure

```text
Airport_Project/
│
├── airport.mp4
├── airport_object_detection_video.mp4
├── videoplayback.mp4
│
├── best.pt
├── last.pt
│
├── README.md
├── data.yaml
│
├── BoxF1_curve.png
├── BoxPR_curve.png
├── BoxP_curve.png
├── BoxR_curve.png
│
├── confusion_matrix.png
├── confusion_matrix_normalized.png
├── labels.jpg
├── results.png
│
├── train_batch0.jpg
├── train_batch1.jpg
├── train_batch2.jpg
├── train_batch540.jpg
├── train_batch541.jpg
├── train_batch542.jpg
│
├── val_batch0_labels.jpg
└── val_batch0_pred.jpg

---

# Dataset

The dataset was created using extracted frames from airport surveillance videos.

## Classes Used

- Airport Vehicle
- Baggage Cart
- Containers
- Airplane

The images were manually annotated in YOLO format for custom object detection training.

---

# Model Training

The YOLO model was trained on custom airport datasets with:

- Increased training samples
- Multiple epochs
- Rescaled image dimensions
- Custom annotations

Training was performed using Ultralytics YOLO.

---

# Installation

## Clone Repository

```bash
git clone https://github.com/your-username/Airport-Ground-Operations-Monitoring.git
cd Airport-Ground-Operations-Monitoring
```

---

# Install Dependencies

```bash
pip install ultralytics
pip install opencv-python
pip install numpy
pip install imageio[ffmpeg]
```

---

# Run Object Detection

```bash
python detect.py
```

---

# Output

The model generates an AI-based airport object detection video with bounding boxes and labels for detected airport operational objects.

Output video:

```text
airport_object_detection_video.mp4
```

---

# Applications

- Smart Airport Surveillance
- Airport Ground Operations Monitoring
- AI-Based Transportation Monitoring
- Automated Safety Monitoring
- Real-Time Object Detection Systems

---

# Future Enhancements

- Real-time CCTV integration
- AI-based alert systems
- Object tracking using DeepSORT
- Airport anomaly detection
- Edge AI deployment
- Live airport monitoring dashboard

---

# Internship Details

- Organization: IIIT Hyderabad iHub
- Domain: Artificial Intelligence & Computer Vision
- Project Type: Internship Research Project

---

# Author

Aisha Erum  
B.E CSE (AI & ML)  
MJCET  

Internship Project – IIIT Hyderabad iHub

---

# License

This project is developed for educational and research purposes.
