# style_transfer_webcam_TF
A Python-based GUI application that uses TensorFlow Hub to apply real-time artistic style transfer to webcam video feeds, allowing users to load custom style images and view the transformed output instantly.
# Real-Time Style Transfer App

A Python-based GUI application that applies real-time artistic style transfer to webcam video feeds using TensorFlow Hub.

## Features
- Load a custom style image.
- Apply the style transfer to a live webcam feed.
- View the transformed output in real time.

## Requirements
- Python 3.10 (`/usr/local/bin/python3.10`)
- Required libraries:
  - `tensorflow-macos`
  - `tensorflow-metal`
  - `tensorflow-hub`
  - `opencv-python`
  - `pillow`

## Installation

1. **Install Python Libraries**:
   Run the following command to install the required dependencies:
   ```bash
   /usr/local/bin/python3.10 -m pip install tensorflow-macos tensorflow-metal tensorflow-hub opencv-python pillow
