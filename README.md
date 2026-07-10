# SHARP-Net: Sewer/Culvert Pipe Defect Detection

## Project Overview
SHARP-Net is a deep learning-based image segmentation project for detecting defects in sewer and culvert pipe images. The project includes synthetic dataset generation, model training, evaluation, and inference to assist automated infrastructure inspection. The model identifies damaged regions, generates defect probability heatmaps, and classifies defects based on severity.

## Features
- Automatic sewer and culvert pipe defect detection
- Synthetic CCTV sewer dataset generation
- Custom SHARP-Net image segmentation model
- Defect probability heatmap generation
- Defect region highlighting
- Defect severity classification
- Model evaluation using IoU and Dice Score
- Inference on uploaded pipe images

## Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
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
The model generates:
- Original pipe image
- Defect probability heatmap
- Binary segmentation mask
- Highlighted defect regions
- Defect severity labels

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

## License
MIT License

## Author
Tirupati Alekhya
