# 3D Vision Libraries

This directory contains libraries and tools for 3D computer vision tasks.

## Categories

- Depth estimation
- 3D reconstruction
- Point cloud processing
- SLAM (Simultaneous Localization and Mapping)
- Structure from Motion

## Libraries

### Open3D
- **Description**: Modern library for 3D data processing
- **Link**: http://www.open3d.org/
- **Install**: `pip install open3d`
- **Use Cases**: Point cloud processing, 3D reconstruction, visualization

### PyTorch3D
- **Description**: Facebook's 3D deep learning library
- **Link**: https://pytorch3d.org/
- **Install**: See official documentation
- **Use Cases**: 3D deep learning, rendering, mesh processing

### MiDaS
- **Description**: Monocular depth estimation
- **Link**: https://github.com/isl-org/MiDaS
- **Install**: Clone repository
- **Use Cases**: Single image depth estimation

### NeRF
- **Description**: Neural Radiance Fields
- **Link**: https://github.com/bmild/nerf
- **Install**: Clone repository
- **Use Cases**: 3D scene reconstruction from images

## Example Usage

```python
# Open3D example
import open3d as o3d
pcd = o3d.io.read_point_cloud("pointcloud.pcd")
o3d.visualization.draw_geometries([pcd])
```
