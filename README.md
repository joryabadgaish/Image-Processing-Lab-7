# Image-Processing-Lab-7

## Description
Notebook covering Canny edge detection, Harris corner detection, and Otsu's thresholding (Q1) using OpenCV.

## Requirements
    pip install opencv-python numpy matplotlib scikit-image

## How to Run
Open the notebook in Jupyter or Colab and run all cells. No image files needed (sample images come from `skimage.data`).

## Q1 – Otsu's Thresholding
Uses `data.coins()`. Otsu picks T = 107 automatically, separating the coins (white) from the background (black). Output shows the original image, histogram, and thresholded image.
