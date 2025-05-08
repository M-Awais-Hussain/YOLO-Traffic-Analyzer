# YOLO Traffic Analyzer 🚗🚦

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![OpenCV](https://img.shields.io/badge/opencv-4.5+-green.svg)
![YOLOv11](https://img.shields.io/badge/yolov11-ultralytics-orange.svg)
![License](https://img.shields.io/badge/license-MIT-purple.svg)

Real-time object tracking and counting system using YOLOv8 that monitors vehicle crossings at a virtual detection line.

## Features

- **YOLOv11 Object Detection**: Pre-trained YOLOv11l model for accurate detection
- **Object Tracking**: Persistent ID tracking across frames
- **Line Crossing Detection**: Counts vehicles crossing a virtual line
- **Class-Specific Counting**: Separate counts for different vehicle classes
- **Visual Feedback**: Bounding boxes, IDs, and real-time counters

## Requirements
```
opencv-python>=4.5.0
ultralytics>=8.0.0
```

## Usage
1. Place your video file in the project directory

2. Run the complete script:
```
Untitled.ipynb
```

3. Controls:

  - Press q to quit

  - Adjust line_y_red in code to change detection line position

## Supported Classes
The system tracks these COCO classes by default:

- Cars

- Trucks

- Buses

- Motorcycles

- Trains

- Bicycles

===

## License
MIT License
