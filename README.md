# Table Recognition in Images

This repository showcases methods for detecting and recognizing tables present within images using image processing and machine learning techniques.

## Overview

Automatically extracting tabular data from images is a challenging yet essential task for digitizing documents and enabling data analysis. This project implements a solution that locates tables in images and extracts their structure—an important capability for automating data extraction from scanned documents, PDFs, and real-world images.

## Features

- Detects table boundaries in document images using deep learning.
- Extracts tabular structure for data conversion and analysis.
- Jupyter Notebook (`Table_recognition .ipynb`) providing clear code, comments, and visualizations.
      
## Requirements

Ensure you have the following installed:

- Python 3.x
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

Install dependencies with:

```bash
pip install opencv-python numpy matplotlib jupyter
```

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Simonatraj/Table-recognition-in-images.git
   cd Table-recognition-in-images
   ```

2. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

3. **Open and run `Table_recognition .ipynb`:**
   - Execute cells sequentially to process sample images, visualize intermediate steps, and observe detected tables.

## Usage

- Loads images containing tables (sample images or your own).
- Preprocesses images (grayscale conversion, edge detection, contour analysis).
- Applies algorithms (e.g., morphological operations, connected components) to identify potential tables.
- Extracts each detected table as a separate image or dataset.
- Visualizes results with bounding boxes and extracted tables.

## Example Results

- Output images showing bounding boxes drawn around detected tables.
- Intermediate steps demonstrating preprocessing and detection pipeline.
- Tables extracted and ready to be converted for further analysis or export.
