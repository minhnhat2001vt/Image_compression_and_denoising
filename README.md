# Image Compression and Denoising with SVD Decomposition

This repository provides a Jupyter Notebook that demonstrates the process of **image compression** and **denoising** using **Singular Value Decomposition (SVD)**. The purpose of the notebook is to explain how to reduce the size of an image without losing significant visual information by using the mathematical technique of SVD. The notebook also explores how SVD can be applied to reduce noise in images.

## Contents

- **Import libraries**: 
  - The required libraries such as `cv2` for image processing, `numpy` for numerical operations, and `matplotlib` for visualization are imported.
  
- **Image Compression**: 
  - Explanation of the SVD process in the context of compressing an image by retaining only the most important singular values.
  
- **Compute SVD**:
  - A function `compute_svd(matrix)` is defined to compute the Singular Value Decomposition (SVD) of a matrix. This function breaks down the image matrix into three components: \(U\), \(S\), and \(V^T\).
  
- **Convert Image to Grayscale**:
  - A function `convertColorToGrayScale(image, ratio)` is provided, which converts a color image to grayscale using a specific ratio for RGB channels. This step prepares the image for further compression and denoising using SVD.
  
- **Compute Image Similarity**:
  - Additional steps and functions to compute similarity between the original image and compressed images using different numbers of singular values. This allows visualization of how compression impacts the image quality.

## Main Functionalities

1. **SVD Decomposition**:
    - The core functionality is applying SVD to break down image matrices and selectively keep only the most important singular values for compression.

2. **Image Conversion**:
    - The notebook includes code to convert images into grayscale for simpler and more effective matrix decomposition.

3. **Image Compression**:
    - By reconstructing the image using fewer singular values, the notebook demonstrates how to effectively reduce image size while maintaining visual clarity.

4. **Denoising**:
    - SVD is also applied in denoising images by eliminating components associated with noise.


