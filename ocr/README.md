# Optical Character Recognition (OCR) Libraries

This directory contains libraries and tools for text detection and recognition.

## Categories

- Text detection
- Text recognition
- Scene text recognition
- Document OCR
- Handwriting recognition

## Libraries

### Tesseract OCR
- **Description**: Open source OCR engine
- **Link**: https://github.com/tesseract-ocr/tesseract
- **Install**: `pip install pytesseract`
- **Use Cases**: General purpose OCR, document text extraction

### EasyOCR
- **Description**: Ready-to-use OCR with 80+ languages
- **Link**: https://github.com/JaidedAI/EasyOCR
- **Install**: `pip install easyocr`
- **Use Cases**: Multi-language OCR, scene text recognition

### PaddleOCR
- **Description**: Practical OCR toolbox by PaddlePaddle
- **Link**: https://github.com/PaddlePaddle/PaddleOCR
- **Install**: `pip install paddleocr`
- **Use Cases**: Text detection and recognition, multilingual support

### TrOCR
- **Description**: Transformer-based OCR
- **Link**: https://huggingface.co/microsoft/trocr-base-handwritten
- **Install**: `pip install transformers`
- **Use Cases**: Handwritten and printed text recognition

## Example Usage

```python
# EasyOCR example
import easyocr
reader = easyocr.Reader(['en'])
result = reader.readtext('image.jpg')
```
