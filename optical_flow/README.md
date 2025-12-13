# Optical Flow Libraries

This directory contains libraries and tools for optical flow estimation.

## Categories

- Dense optical flow
- Sparse optical flow
- Motion tracking
- Video stabilization

## Libraries

### OpenCV Optical Flow
- **Description**: Built-in optical flow algorithms in OpenCV
- **Link**: https://opencv.org/
- **Install**: `pip install opencv-python`
- **Use Cases**: Lucas-Kanade, Farneback, Dense optical flow

### FlowNet 2.0
- **Description**: CNN-based optical flow estimation
- **Link**: https://github.com/NVIDIA/flownet2-pytorch
- **Install**: Clone repository
- **Use Cases**: Learning-based optical flow

### RAFT
- **Description**: Recurrent All-Pairs Field Transforms for Optical Flow
- **Link**: https://github.com/princeton-vl/RAFT
- **Install**: Clone repository
- **Use Cases**: State-of-the-art optical flow estimation

## Example Usage

```python
# OpenCV optical flow example
import cv2
prvs = cv2.cvtColor(frame1, cv2.COLOR_BGR2GRAY)
next = cv2.cvtColor(frame2, cv2.COLOR_BGR2GRAY)
flow = cv2.calcOpticalFlowFarneback(prvs, next, None, 0.5, 3, 15, 3, 5, 1.2, 0)
```
