# 🦺 Safety Helmet Detection using YOLOv8

## Internship Information

* **Intern ID:** CITS4346
* **Intern Name:** Abhishek M Nair
* **Organization:** CODTECH IT Solutions Private Limited
* **Domain:** Artificial Intelligence
* **Internship Duration:** 8 Weeks
* **Internship Period:** 12 June 2026 – 07 August 2026

---

# Project Title

## Advanced Safety Helmet Detection using YOLOv8 and OpenCV

---

# Project Overview

This project aims to detect safety helmets using the YOLOv8 object detection framework. A custom dataset containing helmet images and labels was used to train the model. The system detects helmets and related objects with high accuracy and performs object counting, confidence analysis, and performance evaluation.

---

# Project Scope

* Dataset Preparation
* Object Detection using YOLOv8
* Dataset Analysis
* Class Distribution Visualization
* Model Training and Validation
* Object Counting
* Confidence Analysis
* Training Loss Analysis
* Precision and Recall Analysis
* mAP Performance Evaluation

---

# Technologies Used

* Python
* YOLOv8 (Ultralytics)
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Jupyter Notebook
* VS Code

---

# Dataset Information

### Dataset Structure

```text
train/
│
├── images/
└── labels/

test/
│
├── images/
└── labels/
```

### Classes

| Class ID | Class Name |
| -------- | ---------- |
| 0        | Helmet     |
| 1        | Head       |
| 2        | Person     |

---

# Project Workflow

## Step 1 : Dataset Preparation

The dataset contains training and testing images along with annotation files in YOLO format.

## Step 2 : Dataset Analysis

Class distribution analysis was performed to understand the number of object instances available for training.

## Step 3 : Model Training

YOLOv8 Nano model (`yolov8n.pt`) was fine-tuned on the custom helmet dataset.

Training Parameters:

* Epochs = 50
* Batch Size = 8
* Image Size = 640
* Optimizer = AdamW
* Learning Rate = 0.001

## Step 4 : Model Validation

The trained model was evaluated using:

* Precision
* Recall
* mAP50
* mAP50-95

## Step 5 : Object Detection

The trained model performs detection on test images and displays bounding boxes with confidence scores.

## Step 6 : Object Count Analysis

Detected objects are counted and represented graphically.

## Step 7 : Confidence Analysis

Average confidence scores were calculated for detected classes.

## Step 8 : Performance Visualization

Training loss, mAP, precision, and recall graphs were generated for performance analysis.

---

# Results

The YOLOv8 model successfully detected helmets and achieved good performance on the custom dataset.

Performance analysis included:

* Dataset analysis
* Training metrics
* Validation metrics
* Object detection
* Object counting
* Confidence analysis
* Training loss graph
* mAP graph
* Precision and Recall graph

---

# Screenshots

## Dataset Count Output

![Dataset Count Output](screenshots/Dataset%20count%20output.png)

---

## Class Distribution Graph

![Class Distribution Graph](screenshots/Class%20distribution%20graph.png)

---

## Sample Training Images

![Sample Training Images](screenshots/Sample%20training%20images.png)

---

## Training Completed Output

![Training Completed Output](screenshots/Training%20completed%20output.png)

---

## Validation Metrics

![Validation Metrics](screenshots/Validation%20metrics.png)

---

## Detection Output

![Detection Output](screenshots/Detection%20output.png)

---

## Object Count Graph

![Object Count Graph](screenshots/Object%20count%20graph.png)

---

## Average Confidence Graph

![Average Confidence Graph](screenshots/Average%20confidence%20graph.png)

---

## Training Loss Graph

![Training Loss Graph](screenshots/Training%20loss%20graph.png)

---

## mAP Graph

![mAP Graph](screenshots/mAP%20graph.png)

---

## Precision and Recall Graph

![Precision Recall Graph](screenshots/PrecisionRecall%20graph.png)

---

# Folder Structure

```text
Safety-Helmet-Detection-YOLOv8
│
├── dataset
│   └── safety-helmet-dataset.yaml
│
├── train
│   ├── images
│   └── labels
│
├── test
│   ├── images
│   └── labels
│
├── notebooks
│   └── helmet_detection_yolov8.ipynb
│
├── outputs
│
├── runs
│
├── screenshots
│
├── documentation
│
├── README.md
│
└── requirements.txt
```

---

# Future Enhancements

* Real-Time Webcam Detection
* Video-Based Helmet Detection
* Streamlit Web Application
* Edge Device Deployment
* Industrial Safety Monitoring System

---

# Conclusion

This project demonstrates the application of deep learning and computer vision techniques for safety helmet detection. YOLOv8 was trained on a custom dataset to identify helmets and related objects effectively. Performance metrics and visualizations indicate that the model can be further extended for real-time industrial safety applications.

---

# Author

## Abhishek M Nair

Artificial Intelligence Intern

CODTECH IT Solutions Private Limited

**Intern ID : CITS4346**
