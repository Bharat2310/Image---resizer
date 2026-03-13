
# Image Color Quantization & Dominant Color Extraction 

This repository contains a Python-based image processing tool that uses **K-Means Clustering** to extract the most dominant colors from an image and applies color quantization. 

By grouping similar colors together, this script simplifies the color palette of an image, making it highly useful for design inspiration, image compression, and artistic visual effects.

## ✨ Features
* **Dominant Color Extraction**: Automatically identifies the primary colors making up an image.
* **Color Quantization**: Reconstructs the original image using only the extracted dominant colors.
* **Palette Visualization**: Generates a visually appealing plot displaying the dominant color palette along with their Hex color codes.
* **Easy to tweak**: Simply adjust the `cluster` variable to determine how many colors you want to extract/quantize!

## 🛠️ Technologies & Libraries Used
* **[OpenCV (cv2)](https://opencv.org/)**: For reading, processing, and saving image data.
* **[Scikit-Learn](https://scikit-learn.org/)**: Utilizing the `KMeans` clustering algorithm to group pixels and find color centers.
* **[Matplotlib](https://matplotlib.org/)**: For plotting the final dominant color palette.
* **[NumPy](https://numpy.org/)**: For fast array manipulations and reshaping image dimensions.

## 🚀 Usage

1. Clone this repository:
   ```bash
   git clone [https://github.com/yourusername/color-quantization.git](https://github.com/yourusername/color-quantization.git)
   cd color-quantization
