# Vehicle Detection Bounding Box Dataset

## Overview
This repository contains a dataset of 16 urban street traffic images annotated using **MakeSense.ai**. The project focuses on object detection and labeling in high-density traffic scenes with heavy object occlusion.

## Classes
- `car`
- `motorcycle`

## Dataset Structure & Formats
The annotations are provided in three standard formats for compatibility with various computer vision pipelines:
- **YOLO format (`.txt`):** For YOLOv8/v9 real-time object detection models.
- **Pascal VOC (`.xml`):** For TensorFlow Object Detection API.
- **CSV (`.csv`):** Structured bounding box coordinates (`xmin`, `ymin`, `xmax`, `ymax`).

## Labeling Guidelines Followed
1. **Tight Bounding Boxes:** Tight fit around vehicle boundaries without cutting off visual features.
2. **Occlusion Handling:** Visible parts of overlapping vehicles were labeled accurately.
3. **Class Consistency:** Strict distinction between cars and two-wheelers across dense traffic scenes.
