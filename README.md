# Security Camera Object Detection and Alert System with Yolov8

## Overview

The Security Camera Object Detection and Alert System is a Python-based project designed to enhance security by utilizing computer vision and email notifications. This system leverages various libraries and technologies, such as OpenCV for camera access and object tracking, YOLOv8 for object detection, and email libraries (smtplib, ssl, and email) for sending warning emails. Additionally, it records the camera feed and detected objects, saving it as an MP4 file.

## Features

- Real-time object detection and tracking using YOLOv8.
- Email notifications for:
  - New objects entering the scene.
  - Objects disappearing from the scene.
- Continuous recording of the camera feed with detected objects, saved as an MP4 file.
- Configurable email recipient(s) for alerts.

## Prerequisites

Before running this project, ensure you have the following dependencies installed:

- Python 3.11
- OpenCV  4.8.0.76
- YOLOv8n (for object detection)
- smtplib, ssl, email (for email notifications)
- Ultralytics 8.0.184
- NumPy 1.24.3
- Collections

## Installation

1. Clone the project repository to your local machine:

   ```bash
   git clone https://github.com/g-hano/Security-Camera-with-Yolov8.git
   ```

2. Install the required Python libraries if you haven't already:

   ```bash
   pip install opencv-python
   pip install ultralytics
   ```

## Usage

1. Configure the project settings. You can set the camera source (e.g., camera index or video file path), email settings, and other parameters.

2. Run the Project.ipynb script to start the security camera system:

   The system will begin monitoring the camera feed and send email alerts when new objects enter or disappear from the scene.

3. To stop the system, press `Ctrl + C`.


## Acknowledgments

- YOLOv8: [GitHub repository](https://github.com/ultralytics/ultralytics)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Contact

For any inquiries or issues with this project, please contact me on [LinkedIn](www.linkedin.com/in/cihan-yalçın-666a36246).
