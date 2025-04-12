# Face Detection with OpenCV on Raspberry Pi

## Project Overview

This project demonstrates a **face detection** application using **OpenCV** on a **Raspberry Pi**. The system applies a **real-time bounding box** around detected faces from the video feed captured by a camera. The face detection model uses OpenCV's pre-trained **Haar Cascade Classifier** to identify faces in an image or video stream.

### Key Features:
- Real-time face detection on live video feed.
- Bounding box drawn around detected faces.
- Implemented using the **OpenCV** library on **Raspberry Pi**.

## Prerequisites

Before running the project, you need to install the following dependencies:

- **OpenCV**: For face detection and image processing.
- **Raspberry Pi Camera (PiCamera)**: For live video capture on the Raspberry Pi.

### Installing OpenCV:

You can install OpenCV on your Raspberry Pi with the following command:

```bash
pip install opencv-python
