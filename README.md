# Plant Seedlings Classification

A machine learning project for classification of plant seedlings using computer vision and deep learning techniques.

## Overview

This project implements an image classification system to identify different species of plant seedlings. It's designed to help agronomists to identify plant species at their early growth stages, which is crucial for crop management and weed control.

## Features

- Multi-class classification of plant seedlings
- Image preprocessing and augmentation
- Deep learning model training and evaluation
- Visual analysis of dataset distribution

## Prerequisites

- Python 3.7+
- Required packages:
  ```
  numpy
  pandas
  opencv-python
  matplotlib
  seaborn
  scikit-learn
  tensorflow
  ```

## Project Structure

```
plant-seedlings-classification/
├── train/                  # Training dataset directory
│   ├── category1/         # Images for each plant species
│   ├── category2/
│   └── ...
├── test/                   # Test dataset directory
└── src/                    # Source code
    └── train.py           # Training script
```

## Installation

1. Clone the repository:
   ```bash
   git clone (https://github.com/esco1729/plant-seedlings)
   cd plant-seedlings-classification
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset

The dataset consists of images of plant seedlings at various growth stages, organized into different categories based on species. The data is split into:
- Training set: Located in `train/` directory
- Test set: Located in `test/` directory

Each category represents a different plant species, and the images capture seedlings under various lighting conditions and angles.

## Usage

1. Prepare your data directories:
   - Place training images in `train/[category]/`
   - Place test images in `test/`

2. Run the training script:
   ```python
   python src/train.py
   ```

3. The script will:
   - Load and preprocess the images
   - Display category distribution
   - Train the classification model
   - Generate performance metrics

## Data Visualization

The project includes visualization tools to analyze:
- Distribution of images across different plant seedlings categories
- Sample images from each category
- Training metrics and model performance
