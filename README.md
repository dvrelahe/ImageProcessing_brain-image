# ImageProcessing_brainImage
Applying and comparing common filters on a brain image using OpenCV, NumPy, and Matplotlib

An image processing exercise focused on applying and comparing common filters on a brain image using OpenCV, NumPy, and Matplotlib.

## Overview

This project is a practical image processing notebook that demonstrates how different spatial filters affect an input image. The notebook uses a brain image and compares several filtering methods through both visual output and histogram analysis.

The main goal is to understand how filtering changes:

- image appearance
- intensity distribution
- smoothing behavior
- noise reduction effects

## Features

- **Image Loading**  
  Loads a brain image from local storage.

- **Median Filtering**  
  Applies a median blur to reduce noise while preserving edges.

- **Gaussian Filtering**  
  Applies Gaussian blur for smoothing.

- **Maximum Filtering**  
  Uses dilation to simulate a maximum filter effect.

- **Histogram Comparison**  
  Plots histograms for the original and filtered images.

- **Visual Comparison**  
  Displays filtered images side by side for easier interpretation.

## Technologies Used

- Python
- OpenCV (`cv2`)
- NumPy
- Matplotlib

## Libraries Used
```python
import cv2
import numpy as np
import matplotlib.pyplot as plt
