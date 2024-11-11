# Astrophysics Stars and Galaxy Classification

## Overview

This project aims to leverage machine learning techniques to classify galaxies by their shapes and stars by their luminosities. The project is divided into two main parts: 

1. **GT_NO2 Prediction and Analysis** – Exploring correlations between nitrogen dioxide (NO2) levels on Earth and potential markers of life on other planets.
2. **Classification of Galaxies and Stars** – Using machine learning models like CNN and YOLOv11 to classify galaxies by shape and stars by luminosity.

## Project Structure

- `Part 1`: **GT_NO2 Levels Prediction and Analysis**
  - Analysis of nitrogen dioxide levels and their correlation with life markers on Earth.
  - Machine learning models trained to predict GT_NO2 levels from various input data features.
  
- `Part 2`: **Galaxies and Stars Classification**
  - **Galaxies Classification**: Classifying galaxies by their shapes (spiral, elliptical, irregular, etc.).
  - **Stars Classification**: Classifying stars by their luminosities using deep learning models like CNNs and YOLOv11.

## Requirements

To run the code, the following dependencies need to be installed:

- Python 3.10+
- Required Python libraries (listed in `requirements.txt`):
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `scikit-learn`
  - `tensorflow` (for CNN models)
  - `keras`
  - `yolov11` (for YOLOv11 model)
  - `opencv-python` (for image processing)
  - `astropy` (for astronomy-related calculations)
  - `seaborn`
  
Install the dependencies using:
```bash
pip install -r requirements.txt
