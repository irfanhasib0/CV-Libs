# Face Recognition Libraries

This directory contains libraries and tools for face detection and recognition tasks.

## Categories

- Face detection
- Face recognition
- Facial landmark detection
- Face verification
- Emotion detection

## Libraries

### face_recognition
- **Description**: Simple face recognition library
- **Link**: https://github.com/ageitgey/face_recognition
- **Install**: `pip install face_recognition`
- **Use Cases**: Face detection, recognition, comparison

### dlib
- **Description**: Toolkit with machine learning algorithms
- **Link**: http://dlib.net/
- **Install**: `pip install dlib`
- **Use Cases**: Face detection, facial landmarks, face recognition

### DeepFace
- **Description**: Deep learning face recognition framework
- **Link**: https://github.com/serengil/deepface
- **Install**: `pip install deepface`
- **Use Cases**: Face recognition, verification, analysis

### MediaPipe
- **Description**: Cross-platform ML solutions
- **Link**: https://mediapipe.dev/
- **Install**: `pip install mediapipe`
- **Use Cases**: Face mesh, face detection, facial landmarks

## Example Usage

```python
# face_recognition example
import face_recognition
image = face_recognition.load_image_file("person.jpg")
face_locations = face_recognition.face_locations(image)
face_encodings = face_recognition.face_encodings(image, face_locations)
```
