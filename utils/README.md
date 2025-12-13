# Utility Libraries

This directory contains utility libraries and tools that support various CV tasks.

## Categories

- Data augmentation
- Annotation tools
- Visualization
- Model conversion
- Benchmarking

## Libraries

### Albumentations
- **Description**: Fast image augmentation library
- **Link**: https://albumentations.ai/
- **Install**: `pip install albumentations`
- **Use Cases**: Data augmentation for computer vision

### imgaug
- **Description**: Image augmentation for machine learning
- **Link**: https://github.com/aleju/imgaug
- **Install**: `pip install imgaug`
- **Use Cases**: Advanced image augmentation

### LabelImg
- **Description**: Graphical image annotation tool
- **Link**: https://github.com/tzutalin/labelImg
- **Install**: `pip install labelImg`
- **Use Cases**: Image annotation for object detection

### CVAT
- **Description**: Computer Vision Annotation Tool
- **Link**: https://github.com/opencv/cvat
- **Install**: See documentation
- **Use Cases**: Web-based annotation platform

### torchvision
- **Description**: PyTorch computer vision library
- **Link**: https://pytorch.org/vision/
- **Install**: `pip install torchvision`
- **Use Cases**: Datasets, transforms, pre-trained models

## Example Usage

```python
# Albumentations example
import albumentations as A
transform = A.Compose([
    A.RandomCrop(width=256, height=256),
    A.HorizontalFlip(p=0.5),
    A.RandomBrightnessContrast(p=0.2),
])
augmented = transform(image=image)
```
