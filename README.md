### README: Weapon Detection AI

---

## Overview
**Weapon Detection AI** is an advanced security solution designed to enhance surveillance systems by integrating state-of-the-art weapon detection capabilities. Utilizing the robust YOLOv8 model, this AI tool specializes in identifying weapons within video streams, aiming to reduce false positives and maximize detection accuracy.

## Features
- **High Accuracy**: Leverages the powerful YOLOv8 model to ensure precise weapon detection with minimal false positives.
- **Real-Time Processing**: Capable of processing live video feeds in real-time, ensuring timely identification of threats.
- **Optimized for Diverse Conditions**: Tested and refined to perform reliably across various lighting and environmental conditions.
- **Surveillance Optimization**: Ideal for integration into existing or new surveillance systems in settings such as schools, public spaces, and corporate environments.

## Technical Specifications
- **Model**: YOLOv8
- **Platform**: Optimized for Apple Silicon using MPS (Metal Performance Shaders) for enhanced performance on GPU.
- **Input**: Supports various video stream inputs.
- **Output**: Provides coordinates of detected weapons within the video frame.

## Installation
To set up the Weapon Detection AI on your system, follow these steps:

```bash
# Clone the repository
git clone https://github.com/Hassan220022/weapon-detection-ai.git

# Navigate into the project directory
cd weapon-detection-ai
```

## Usage
To run the weapon detection model on a video file:

```python
from detector import run_detection

# Path to your video file
video_path = 'path/to/video.mp4'

# Perform detection
run_detection(video_path)
```

---
