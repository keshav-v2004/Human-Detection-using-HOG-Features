![Python](https://img.shields.io/badge/Python-3.10-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green)
![scikit-image](https://img.shields.io/badge/scikit--image-HOG-orange)
![NumPy](https://img.shields.io/badge/NumPy-Data%20Processing-blue)
![Google Colab](https://img.shields.io/badge/Google-Colab-orange)

# Human Detection using HOG Features

This project demonstrates human detection using **Histogram of Oriented Gradients (HOG)** features on the **INRIA Person Dataset**. The notebook loads positive and negative samples, extracts HOG descriptors, and visualizes the resulting feature representations to understand how HOG captures human shapes and edges.

## Features

- Load positive and negative samples from the INRIA Person Dataset
- Extract HOG features using `scikit-image`
- Visualize HOG feature maps
- Compare human and non-human image features
- Analyze HOG feature vector dimensions
- Learn the fundamentals of traditional object detection

## Dataset

This project uses the INRIA Person Dataset.

Dataset paths used in the notebook:

```python
pos_path = "/content/drive/MyDrive/INRIA_dataset/INRIAPerson/train_64x128_H96/pos"
neg_path = "/content/drive/MyDrive/INRIA_dataset/INRIAPerson/Train/neg"
```

## Dependencies

Install the required libraries:

```bash
pip install scikit-image opencv-python matplotlib numpy
```

## Workflow

1. Mount Google Drive
2. Load positive and negative images
3. Preprocess images
4. Compute HOG features
5. Visualize HOG representations
6. Compare feature patterns between classes
7. Analyze feature vector dimensions

## Example Output

The notebook displays:

- Original human images
- HOG visualizations of human images
- Original non-human images
- HOG visualizations of non-human images
- HOG feature vector length

## How to Run

1. Open the notebook in Google Colab
2. Mount Google Drive
3. Place the INRIA Person Dataset in the specified directory
4. Install the required dependencies
5. Run all cells sequentially

## Learning Objective

This project serves as an introduction to traditional computer vision techniques and demonstrates how HOG features can be used for human detection tasks before applying machine learning classifiers such as SVMs.

<p align="center">
  <img src="https://github.com/user-attachments/assets/011c2de4-3796-44ab-9dd5-805980b385bb" width="45%" />
  <img src="https://github.com/user-attachments/assets/9a2f90c9-4db0-457e-ba24-dc9af00daa26" width="45%" />
</p>

