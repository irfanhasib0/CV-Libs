# Object Detection Libraries

This directory contains libraries and tools for object detection tasks.

## Categories

- Real-time object detection
- Pre-trained models
- Custom object detection
- Multi-object tracking

## Libraries

### YOLO (Ultralytics)
- **Description**: You Only Look Once - Real-time object detection
- **Link**: https://github.com/ultralytics/ultralytics
- **Install**: `pip install ultralytics`
- **Use Cases**: Real-time object detection, multiple object classes

### Detectron2
- **Description**: Facebook AI Research's next generation library
- **Link**: https://github.com/facebookresearch/detectron2
- **Install**: See official documentation
- **Use Cases**: State-of-the-art detection and segmentation algorithms

### TensorFlow Object Detection API
- **Description**: Open source framework built on TensorFlow
- **Link**: https://github.com/tensorflow/models/tree/master/research/object_detection
- **Install**: See official documentation
- **Use Cases**: Training custom object detectors, pre-trained models

### MMDetection
- **Description**: Open source object detection toolbox
- **Link**: https://github.com/open-mmlab/mmdetection
- **Install**: `pip install mmdet`
- **Use Cases**: Wide variety of detection architectures

## Example Usage

```python
# YOLO example
from ultralytics import YOLO
model = YOLO('yolov8n.pt')
results = model('image.jpg')
```
