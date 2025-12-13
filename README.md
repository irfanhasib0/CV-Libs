# CV-Libs

A curated collection of computer vision third-party libraries and tools, organized by category for easy reference and use.

## 📚 Overview

This repository serves as a comprehensive storage and reference for popular computer vision libraries across different domains. Each category contains documentation, installation instructions, use cases, and example code.

## 📂 Categories

### 🖼️ [Image Processing](./image_processing/)
General image processing libraries for filtering, transformations, and basic operations.
- OpenCV
- Pillow (PIL)
- scikit-image
- imageio

### 🎯 [Object Detection](./object_detection/)
Libraries for detecting and localizing objects in images and videos.
- YOLO (Ultralytics)
- Detectron2
- TensorFlow Object Detection API
- MMDetection

### 👤 [Face Recognition](./face_recognition/)
Tools for face detection, recognition, and facial landmark detection.
- face_recognition
- dlib
- DeepFace
- MediaPipe

### ✂️ [Segmentation](./segmentation/)
Libraries for semantic and instance segmentation.
- Segment Anything Model (SAM)
- U-Net
- MMSegmentation
- Mask R-CNN

### 🏃 [Pose Estimation](./pose_estimation/)
Human pose and keypoint estimation libraries.
- OpenPose
- MediaPipe Pose
- MMPose
- AlphaPose

### 🌊 [Optical Flow](./optical_flow/)
Motion estimation and optical flow algorithms.
- OpenCV Optical Flow
- FlowNet 2.0
- RAFT

### ✨ [Image Enhancement](./image_enhancement/)
Libraries for image restoration, super-resolution, and enhancement.
- Real-ESRGAN
- GFPGAN
- DeblurGAN
- waifu2x

### 🎲 [3D Vision](./3d_vision/)
3D computer vision, depth estimation, and point cloud processing.
- Open3D
- PyTorch3D
- MiDaS
- NeRF

### 🎬 [Video Analysis](./video_analysis/)
Video understanding, action recognition, and object tracking.
- PyTorchVideo
- SlowFast
- SORT/DeepSORT
- moviepy

### 📝 [OCR (Optical Character Recognition)](./ocr/)
Text detection and recognition from images.
- Tesseract OCR
- EasyOCR
- PaddleOCR
- TrOCR

### 🔧 [Utilities](./utils/)
Supporting tools for augmentation, annotation, and visualization.
- Albumentations
- imgaug
- LabelImg
- CVAT
- torchvision

## 🚀 Quick Start

### Installation

Navigate to the category of interest and install the required dependencies:

```bash
# Example: Installing image processing libraries
cd image_processing
pip install -r requirements.txt
```

### Usage

Each category folder contains:
- `README.md` - Detailed information about libraries in that category
- `requirements.txt` - Python dependencies for that category
- Example code snippets

## 📖 How to Use This Repository

1. **Browse by Category**: Navigate to the folder matching your use case
2. **Read Documentation**: Each category has detailed README with library descriptions
3. **Install Dependencies**: Use the requirements.txt file in each category
4. **Try Examples**: Test the example code provided in each category's README

## 🤝 Contributing

Contributions are welcome! To add a new library or update existing information:

1. Fork the repository
2. Add your library to the appropriate category
3. Update the category's README.md with:
   - Library name and description
   - Installation instructions
   - Use cases
   - Example code
4. Update requirements.txt if needed
5. Submit a pull request

## 📋 Library Criteria

Libraries included in this collection should:
- Be actively maintained
- Have good documentation
- Be widely used in the CV community
- Support Python (primary focus)
- Be open source (when possible)

## 🔗 Resources

### Learning Resources
- [OpenCV Documentation](https://docs.opencv.org/)
- [PyTorch Vision Tutorial](https://pytorch.org/vision/stable/index.html)
- [TensorFlow Computer Vision](https://www.tensorflow.org/tutorials/images)

### Community
- [Computer Vision subreddit](https://www.reddit.com/r/computervision/)
- [Papers with Code - Computer Vision](https://paperswithcode.com/area/computer-vision)

## ⚖️ License

This repository is for educational and reference purposes. Each library listed has its own license - please refer to individual library documentation for licensing information.

## 📮 Contact

For questions or suggestions, please open an issue in this repository.

---

**Note**: This repository serves as a reference and organizational tool. Always refer to official documentation for the most up-to-date installation and usage instructions.