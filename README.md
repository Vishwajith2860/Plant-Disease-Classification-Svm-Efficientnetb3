COMP8831 Machine Learning Project

## Project Title

Deep Learning-Based Plant Disease Detection and Classification Using EfficientNetB3 with SVM Baseline Comparison

## Group Members

* Dhanushka Vishwajith Bandara Jayasinghe - 1595273
* Mridul Raj Poudel - 1608247

## Project Overview

This project investigates automated plant disease classification using leaf images from the PlantVillage dataset. Two approaches were implemented and compared:

1. Support Vector Machine (SVM) using handcrafted texture and colour features.
2. EfficientNetB3 using transfer learning and deep learning-based feature extraction.

The objective was to evaluate and compare the effectiveness of traditional machine learning and deep learning techniques for plant disease detection.

## Files Included

* `SVMCode.ipynb` – Implementation of the SVM baseline model.
* `EfficientNetB3.ipynb` – Implementation of the EfficientNetB3 transfer learning model.
* `COMP8831 Machine Learning Presentation.pptx` – Project presentation slides.

## Dataset

PlantVillage Dataset

GitHub Repository:
https://github.com/spMohanty/PlantVillage-Dataset

The dataset contains 54,305 images across 38 plant disease and healthy plant classes.

## Software Requirements

Recommended Python Version:

* Python 3.10 or later

Required Libraries:

* numpy
* pandas
* matplotlib
* seaborn
* scikit-learn
* scikit-image
* opencv-python
* tensorflow
* keras
* jupyter

## Running the Project

### SVM Model

1. Open `SVMCode.ipynb`.
2. Update the dataset path if necessary.
3. Run all notebook cells sequentially from top to bottom.
4. The notebook will:

   * Load the dataset
   * Extract LBP and RGB histogram features
   * Perform feature scaling
   * Train and optimize the SVM classifier
   * Evaluate training, validation, and test performance

### EfficientNetB3 Model

1. Open `EfficientNetB3.ipynb`.
2. Update the dataset path if necessary.
3. Run all notebook cells sequentially.
4. The notebook will:

   * Load and preprocess the dataset
   * Train the EfficientNetB3 model using transfer learning
   * Perform fine-tuning
   * Evaluate classification performance

## Reproducibility

Random seeds were fixed where applicable to improve reproducibility. Running the notebooks on the same dataset and software environment should reproduce results similar to those reported in the project report.

## Notes

The PlantVillage dataset is not included in this submission due to its size. Please download the dataset from the provided GitHub repository before running the notebooks.
