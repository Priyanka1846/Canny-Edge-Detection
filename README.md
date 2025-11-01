# Canny Edge Detection with OpenCV

A simple and focused Jupyter Notebook demonstrating image processing, specifically resizing an image and applying the Canny Edge Detection filter using the OpenCV library (`cv2`).

## 🖼️ Project Overview

This repository contains a single Jupyter Notebook (`Canny Edge Detection.ipynb`) that illustrates the basic steps required to perform edge detection on an image. It's an excellent starting point for computer vision beginners interested in fundamental image manipulation techniques.

## ✨ Features

* **Image Loading:** Reads a source image using OpenCV.
* **Image Resizing:** Scales the input image to a fixed size (`600x400`).
* **Grayscale Conversion:** Prepares the image for the Canny algorithm.
* **Canny Edge Detection:** Applies the industry-standard Canny filter to extract object boundaries.
* **Visualization:** Displays the original (resized) image alongside the final edge map using `matplotlib`.

## ⚙️ Prerequisites

To run this notebook, you need Python installed, along with the following libraries:

| Library | Purpose |
| :--- | :--- |
| **`opencv-python`** | Core computer vision functions (`cv2`). |
| **`numpy`** | Numerical operations. |
| **`matplotlib`** | Plotting and image display. |

### Installation

You can install all necessary packages using `pip`:

```bash
pip install opencv-python numpy matplotlib
