# Image Enhancement Libraries

This directory contains libraries and tools for image enhancement and restoration.

## Categories

- Image denoising
- Super-resolution
- HDR imaging
- Low-light enhancement
- Image restoration

## Libraries

### Real-ESRGAN
- **Description**: Practical image restoration with enhanced SRGAN
- **Link**: https://github.com/xinntao/Real-ESRGAN
- **Install**: `pip install realesrgan`
- **Use Cases**: Image super-resolution, enhancement

### GFPGAN
- **Description**: Face restoration with generative models
- **Link**: https://github.com/TencentARC/GFPGAN
- **Install**: `pip install gfpgan`
- **Use Cases**: Face restoration, enhancement

### DeblurGAN
- **Description**: Motion deblurring using GANs
- **Link**: https://github.com/KupynOrest/DeblurGAN
- **Install**: Clone repository
- **Use Cases**: Motion blur removal

### waifu2x
- **Description**: Image super-resolution for anime-style art
- **Link**: https://github.com/nagadomi/waifu2x
- **Install**: See documentation
- **Use Cases**: Anime image upscaling, denoising

## Example Usage

```python
# Real-ESRGAN example
from realesrgan import RealESRGAN
model = RealESRGAN('cuda', scale=4)
enhanced_image = model.predict(image)
```
