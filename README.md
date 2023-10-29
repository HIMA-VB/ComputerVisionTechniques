# ComputerVisionTechniques


```markdown
# Image Processing with OpenCV

This repository contains Python code snippets for various image processing tasks using OpenCV, a popular computer vision library.

## 1. Piecewise Linear Transformation
- File: `piecewise_linear_transform.py`
- Description: This script performs piecewise linear transformation on an image to enhance its contrast. It takes an input image, a threshold, and slope values for the low and high regions of the transformation.

## 2. Histogram Equalization
- File: `histogram_equalization.py`
- Description: This script demonstrates the application of histogram equalization to enhance the contrast of an image. It also plots the original and equalized histograms for comparison.

## 3. Filtering Techniques
- File: `image_filtering.py`
- Description: This script applies mean, median, and Laplacian filters to an image. It includes the original image, mean-filtered, median-filtered, and Laplacian-filtered images for comparison.

## 4. Edge Detection
- File: `edge_detection.py`
- Description: This script performs edge detection using Sobel operators and the Canny edge detector. It displays the original image and the edge-detected image side by side.

## 5. Geometric Transformations
- File: `geometric_transformations.py`
- Description: This script demonstrates geometric transformations, including rotation, scaling, translation, and shearing of an input image.

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/opencv-image-processing.git
   ```

2. Navigate to the project directory:
   ```bash
   cd opencv-image-processing
   ```

3. Run the desired script by executing it with Python:
   ```bash
   python piecewise_linear_transform.py
   ```

4. View the results for the specific image processing task.

## Dependencies
Ensure you have OpenCV and any other necessary libraries installed. You can install OpenCV with the following command:
```bash
pip install opencv-python
```

## License
This project is open-source and available under the [MIT License](LICENSE).

---
