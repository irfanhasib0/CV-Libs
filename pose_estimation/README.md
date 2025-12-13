# Pose Estimation Libraries

This directory contains libraries and tools for human pose estimation.

## Categories

- 2D pose estimation
- 3D pose estimation
- Multi-person pose estimation
- Hand pose estimation

## Libraries

### OpenPose
- **Description**: Real-time multi-person keypoint detection
- **Link**: https://github.com/CMU-Perceptual-Computing-Lab/openpose
- **Install**: See official documentation
- **Use Cases**: Body, face, hand, and foot keypoint detection

### MediaPipe Pose
- **Description**: Google's ML solution for pose estimation
- **Link**: https://mediapipe.dev/
- **Install**: `pip install mediapipe`
- **Use Cases**: Real-time pose tracking, fitness applications

### MMPose
- **Description**: Open source pose estimation toolbox
- **Link**: https://github.com/open-mmlab/mmpose
- **Install**: `pip install mmpose`
- **Use Cases**: 2D/3D pose estimation, various architectures

### AlphaPose
- **Description**: Multi-person pose estimation system
- **Link**: https://github.com/MVIG-SJTU/AlphaPose
- **Install**: Clone repository
- **Use Cases**: Accurate multi-person pose estimation

## Example Usage

```python
# MediaPipe Pose example
import mediapipe as mp
mp_pose = mp.solutions.pose
pose = mp_pose.Pose()
results = pose.process(image)
```
