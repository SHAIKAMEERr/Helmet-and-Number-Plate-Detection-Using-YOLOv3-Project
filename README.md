
---

# Helmet Detection System

## Overview

This is a Python script for a helmet detection system using YOLO (You Only Look Once) object detection and a pre-trained CNN (Convolutional Neural Network) model for classifying helmet presence in detected regions. The system processes a video feed, identifies individuals, and checks whether they are wearing a helmet.

## Prerequisites

- Python 3.x
- OpenCV
- NumPy
- imutils
- TensorFlow
- Google Colab (for displaying images)

## Setup

1. Clone the repository:

   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Ensure that the necessary model weights and configuration files are available in the specified paths.
2. Modify the video file path in the script to point to your desired input video (`/video[1].mp4`).
3. Run the script:

   ```bash
   python helmet_detection.py
   ```

   Press `Esc` to exit the video feed.

## Output

The script processes the video, detects individuals, identifies helmets, and highlights them with bounding boxes. The processed video is saved as `output.avi`.

## Email Notification

The script includes functionality to send an email notification when a person is detected without a helmet. Configure the sender's and receiver's email addresses and password in the script.

---

MD5 Hash for the Code: **[MD5_HASH]**

---

