---

# Helmet Detection System

This project focuses on detecting helmets in images or videos using computer vision techniques and a pre-trained deep learning model.

## Prerequisites

- Python 3.x
- OpenCV
- NumPy
- imutils
- TensorFlow
- CUDA (for GPU acceleration)

## Setup

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. Download the YOLOv3 weights and configuration file from [here](https://pjreddie.com/darknet/yolo/) and place them in the project directory.

3. Download the pre-trained helmet detection model (`helmet-nonhelmet_cnn.h5`) and place it in the project directory.

4. Install dependencies:

   ```bash
   pip install opencv-python numpy imutils tensorflow
   ```

5. Run the code:

   ```bash
   python helmet_detection.py
   ```

## Usage

1. Modify the `video.mp4` file or replace it with your own video file.
2. Ensure that the YOLOv3 weights and configuration files are appropriately named (`yolov3-custom_7000.weights` and `yolov3-custom.cfg`).
3. Make sure the pre-trained model file is named `helmet-nonhelmet_cnn.h5`.
4. Run the script and observe the helmet detection in the output video (`output.avi`).

## Important Note

This code assumes the presence of a CUDA-enabled GPU for accelerated processing. If you don't have a compatible GPU, you may need to adjust the code to run on CPU.

## Credits

- YOLOv3: [YOLO: Real-Time Object Detection](https://pjreddie.com/darknet/yolo/)
- Helmet Detection Model: [Helmet Detection CNN](https://example-link-to-your-model.com)

Feel free to contribute, report issues, or suggest improvements!

---
