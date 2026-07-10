# SHARP-Net: Sewer/Culvert Pipe Defect Detection

## Project Overview
SHARP-Net is a deep learning-based image segmentation project that detects defects in sewer and culvert pipe images. The model identifies damaged regions and classifies them based on severity to assist in automated infrastructure inspection.

## Features
- Detects defects in sewer and culvert pipes
- Generates a defect probability heatmap
- Highlights detected defect regions
- Classifies defects into:
  - Minor
  - Moderate
  - Severe

## Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Google Colab

## Project Workflow
1. Upload a pipe image.
2. Preprocess the image.
3. Run the SHARP-Net segmentation model.
4. Generate a probability heatmap.
5. Highlight defect regions.
6. Display defect severity.

## Project Output
The model displays:
- Original pipe image
- Defect probability heatmap
- Defects highlighted with severity labels

## How to Run
1. Open the notebook in Google Colab.
2. Install the required libraries.
3. Upload a pipe image.
4. Run all notebook cells.
5. View the detected defects and severity.

## Future Improvements
- Train on larger real-world datasets.
- Improve detection accuracy.
- Deploy as a web application.
- Support real-time video inspection.

## Author
Alekhya
