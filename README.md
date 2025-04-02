# Shape-Based Object Detection & Tracking with OpenCV on Raspberry Pi 4

## Overview
This project focuses on shape-based object detection and tracking using OpenCV on a Raspberry Pi 4. Shape-based tracking recognizes and follows objects based on their geometric properties. By leveraging OpenCV, an open-source computer vision library, and the Raspberry Pi, we create a real-time tracking system suitable for applications in surveillance, robotics, and interactive installations.

## Components Required
To build this project, you will need the following components:

| S.N. | Component               | Quantity | Purchase Link |
|------|-------------------------|----------|--------------|
| 1    | Raspberry Pi 4         | 1        | [Amazon](#) / [SunFounder](#) |
| 2    | Raspberry Pi Camera    | 1        | [Amazon](#) / [SunFounder](#) |
| 3    | SD Card (16/32 GB)     | 1        | [Amazon](#) / [SunFounder](#) |
| 4    | 5V, 3A DC Adapter      | 1        | [Amazon](#) / [SunFounder](#) |
| 5    | LCD Display (Optional) | 1        | [Amazon](#) / [SunFounder](#) |
| 6    | Mouse & Keyboard (Optional) | 1 | [Amazon](#) / [SunFounder](#) |

## Raspberry Pi Camera Setup
The Raspberry Pi Camera is essential for capturing video feeds. To connect and enable the camera:
1. Attach the Camera Module to the Camera Connector on the Raspberry Pi 4.
2. Open the Raspberry Pi Configuration Tool:
   ```bash
   sudo raspi-config
   ```
3. Navigate to `Interfacing Options > Camera` and enable it.

## Installing OpenCV and Dependencies
OpenCV is required for object detection, tracking, and image processing. Follow the guide below to install OpenCV on your Raspberry Pi 4:

1. Install OpenCV:
   ```bash
   sudo apt update
   sudo apt install python3-opencv
   ```
2. Install `picamera` for accessing the Raspberry Pi Camera:
   ```bash
   pip3 install picamera
   ```

Once installed, you are ready to implement shape-based object detection and tracking on your Raspberry Pi 4!



