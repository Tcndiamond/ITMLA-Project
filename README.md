
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

## What I Learned

Through this project, I gained practical experience in applying machine learning and image processing techniques to solve real-world problems.

Some of the key things I learned include:

- **Image Preprocessing:** I learned how to use histogram equalisation and Gaussian filtering to improve image quality, enhance important features, and reduce noise.
- **Data Preparation:** I developed a better understanding of image normalisation and why preparing data correctly is important for machine learning.
- **Feature Extraction:** I explored how Histogram of Oriented Gradients (HOG) can extract useful information about edges, shapes, and textures from images.
- **Machine Learning:** I gained experience working with a Random Forest classifier and understanding how models learn to distinguish between different categories of images.
- **Model Evaluation:** I learned the importance of separating training and testing data to assess how well a model can make predictions on unseen images.
- **Problem-Solving:** I strengthened my Python programming and analytical thinking skills by working through the different stages of an image classification project.

Overall, this project helped me understand how different image processing and machine learning techniques work together to turn raw image data into useful information. It also strengthened my interest in artificial intelligence, computer vision, and developing intelligent systems that can solve practical problems.
