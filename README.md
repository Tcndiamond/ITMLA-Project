
# Concrete Crack Detection Using Machine Learning

## Project Overview

This academic project explores how image processing and machine learning can be used to distinguish between concrete surfaces with cracks and those without cracks.

The project applies image enhancement, feature extraction, and a Random Forest classifier to image data.

## Technologies Used

- Python
- OpenCV
- NumPy
- Scikit-learn
- Scikit-image
- Matplotlib
- Jupyter Notebook

## Methodology

### 1. Image Loading
Images are loaded from two categories:
- Defective concrete
- Defect-free concrete

### 2. Image Preprocessing
Histogram equalisation improves image contrast, while Gaussian filtering reduces noise.

### 3. Image Normalisation
Pixel values are normalised to prepare the images for feature extraction.

### 4. Feature Extraction
Histogram of Oriented Gradients (HOG) is used to capture image features relating to edges, shapes, and textures.

### 5. Model Development
The project uses a Random Forest classifier with 100 estimators.

An 80/20 training and testing split is specified in the notebook.

## Project Results

[Add verified results from your original project, including accuracy, precision, recall, or other findings.]

## Project Files

- `Question 3.ipynb` — Python implementation
- `ITMLA3-B11 Project.pdf` — Academic project document

## Reproducibility

The notebook currently uses local dataset paths and requires adjustments before it can run on another computer.

## What I Learned

[Explain what you personally learned about image preprocessing, feature extraction, model training, and evaluating predictions.]
