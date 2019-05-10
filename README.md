# kabamaru
A small C++ library for processing 3D point clouds. Supported functionality includes:
* A SLAM implementation (point cloud stitching using ICP and/or SIFT correspondences)
* Detection of boxes (cuboids) in point clouds
* Constrained box fitting for point cloud segments

### Dependencies:
* PCL
* OpenCV
* [SiftGPU](https://github.com/kzampog/SiftGPU)
* [namaris](https://github.com/aecins/namaris)
* CUDA (optional)
