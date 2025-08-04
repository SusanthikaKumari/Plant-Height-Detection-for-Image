# Plant Height Detection using OpenCV (Image processing)

This simple project uses Python and OpenCV to detect the tallest plant in an image using color segmentation and contour analysis.

## How it works

- Reads an image
- Applies HSV masking for green color
- Finds all contours
- Detects the one with the largest area
- Displays bounding box and height

## Requirements

- OpenCV
- NumPy

## How to Run the Project

### Run the Python Script (Command Line)

If you're using a `.py` file:

```bash
python plant_height_detection.py

### Run the Jupyter Notebook

Make sure you have Jupyter installed. You can run the notebook with:

```bash
jupyter notebook

