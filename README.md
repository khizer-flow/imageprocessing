# Basic Image Processing in Python

This project demonstrates fundamental image processing techniques using Python 3 and Jupyter Notebook. It covers loading images, converting RGB images to grayscale, brightness adjustment, image inversion, histogram plotting, and edge detection.

## Features

- Load and display JPEG images
- Convert RGB images to grayscale (simple average)
- Brighten grayscale images
- Invert grayscale images
- Plot histograms of grayscale values
- Detect horizontal and vertical edges

## Requirements

- Python 3.x
- numpy
- matplotlib
- imageio
- scipy

## Usage

1. Place your images (`pic1.jpeg`, `pic2.jpeg`, `pic3.jpeg`) in the project directory.
2. Open and run the notebook `DIP2.ipynb` in Jupyter or VS Code.
3. Follow the notebook cells to see image processing steps and visualizations.

## File Structure

- `DIP2.ipynb`: Main notebook with all code and explanations
- `pic1.jpeg`, `pic2.jpeg`, `pic3.jpeg`: Sample images for processing

## Example Workflow

1. **Import Libraries**  
   Uses numpy, matplotlib, imageio, and scipy.

2. **Load Images**  
   Loads images into numpy arrays.

3. **Display Images**  
   Shows original images using matplotlib.

4. **Convert to Grayscale**  
   Applies average method for grayscale conversion.

5. **Brightness Adjustment**  
   Multiplies grayscale values to brighten images.

6. **Image Inversion**  
   Inverts grayscale images using `255 - value`.

7. **Histogram Plotting**  
   Plots pixel intensity histograms.

8. **Edge Detection**  
   Applies horizontal and vertical edge kernels.



---

For questions or improvements, please edit `DIP2.ipynb` or
