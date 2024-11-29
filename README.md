# Computer Vision and Image Processing Pipeline

This project implements a comprehensive pipeline for processing and analyzing images using various computer vision and image processing techniques.

## Features

1. **Denoising**
   - Apply various filters (both inbuilt and custom-implemented) to denoise images.
   - Compute and evaluate the denoising performance using appropriate scores.

2. **Gradient and Kurtosis Analysis**
   - Generate gradient images to extract edge information.
   - Measure the kurtosis of the images to quantify statistical characteristics.

3. **Segmentation**
   - Perform image segmentation using both noise-sensitive and noise-invariant methods.
   - Validate segmentation results by calculating segmentation validation scores.

4. **Classification using Machine Learning**
   - Classify segmented images based on Histograms of Curvature.
   - Utilize a K-Nearest Neighbors (KNN) Classifier for classification tasks.

5. **Object Classification with Deep Learning**
   - Implement image object classification using a combination of CNN and ANN layers.
   - Employ Transfer Learning with the **InceptionV3 model** for enhanced performance.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
