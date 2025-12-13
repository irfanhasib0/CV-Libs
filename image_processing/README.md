# Image Processing Libraries

This directory contains libraries and tools for general image processing tasks.

## Categories

- Image filtering and smoothing
- Edge detection
- Morphological operations
- Image transformations
- Color space conversions

## Libraries

### OpenCV
- **Description**: Open Source Computer Vision Library
- **Link**: https://opencv.org/
- **Install**: `pip install opencv-python`
- **Use Cases**: General purpose image processing, filtering, transformations

### Pillow (PIL)
- **Description**: Python Imaging Library
- **Link**: https://python-pillow.org/
- **Install**: `pip install Pillow`
- **Use Cases**: Image loading, saving, basic manipulations

### scikit-image
- **Description**: Image processing in Python
- **Link**: https://scikit-image.org/
- **Install**: `pip install scikit-image`
- **Use Cases**: Advanced image processing algorithms, scientific computing

### imageio
- **Description**: Library for reading and writing image data
- **Link**: https://imageio.github.io/
- **Install**: `pip install imageio`
- **Use Cases**: Reading and writing various image formats

## Example Usage

```python
# OpenCV example
import cv2
img = cv2.imread('image.jpg')
gray = cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)
blurred = cv2.GaussianBlur(gray, (5, 5), 0)
```
