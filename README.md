**Table Recognition in Images**

This project, "Table Recognition in Images," focuses on detecting and recognizing tables within images using image processing and machine learning techniques. Here’s a quick summary and guidance for running it, especially with Google Colab:

### Project Overview

- **Goal:** Automatically extract tabular data from images for digitizing documents and enabling data analysis.
- **Core Tasks:**
  - Detect table boundaries in document images (deep learning).
  - Extract tabular structures for further data conversion and analysis.
  - Provide visual, step-by-step notebooks.

### Key Features

- Detects tables within images.
- Extracts their structure into usable datasets.
- Includes a Jupyter Notebook (`Table_recognition.ipynb`) with explanations and visualizations.

### Requirements

- **Python 3.x**
- **OpenCV**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook** (for local use—can be swapped for Google Colab)

Install dependencies (for local setup):

```bash
pip install opencv-python numpy matplotlib jupyter
```

### Using the Project on Google Colab

Since you want to use Google Colab (and not Jupyter Notebook locally), here’s what you should do:

1. **Open Google Colab:**  
   Go to [Google Colab](https://colab.research.google.com).

2. **Access the Notebook:**
   - Click "File" → "Open notebook."
   - Select the **GitHub** tab.
   - Enter the repository URL:  
     `https://github.com/Simonatraj/table-recognition-in-images`
   - Select `Table_recognition.ipynb` from the list.

3. **Install Dependencies in Colab:**  
   At the top of your notebook, run a cell with:

   ```python
   !pip install opencv-python numpy matplotlib
   ```

4. **Upload Images (Optional):**  
   If you want to process your own images, use Colab’s upload feature to add them to the session.

5. **Run Cells Sequentially:**  
   The notebook demonstrates:
   - Loading images.
   - Preprocessing (grayscale conversion, edge detection).
   - Table detection (morphology, connected components).
   - Extracting tables as images or datasets.
   - Visualizing bounding boxes and extracted tables.

### Example Outputs

- Images with **bounding boxes** highlighting detected tables.
- Visualizations showing each step in the detection workflow.
- **Extracted tables** ready for downstream data analysis.

**Summary:**  
This repository provides everything you need to detect and extract tabular data from images using Google Colab. You only need to copy the notebook to Colab, install requirements in the notebook itself, and you can process your own images without needing a local Jupyter installation. 
