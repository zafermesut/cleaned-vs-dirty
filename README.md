# Cleaned vs Dirty Plate Classification

This repository contains a deep learning-based classifier designed to distinguish between clean and dirty plates. The model aims to optimize dishwashing efficiency by automating the task of identifying clean plates, saving time and effort for the user.

## Project Overview

Dishes can often pile up, making dishwashing a tedious task. This classifier provides a solution by detecting which plates are already clean, allowing users to focus only on the dirty dishes. The model was trained on a balanced dataset consisting of 20 clean and 20 dirty plates and tested on a larger dataset, achieving an accuracy of **78.36%**.

### Dataset

The dataset consists of:

- **Training set:** 20 images each of clean and dirty plates.
- **Test set:** Hundreds of images for evaluating model performance.

### Approach

A deep learning model was trained to classify the images into clean and dirty categories using a few-shot learning setup. Given the limited training data, the model leverages data augmentation and transfer learning techniques to improve generalization and accuracy.

### Model Performance

- **Final Accuracy:** 78.36%

### Usage

To reproduce this work or experiment further, download the dataset, load the model, and follow the training and evaluation pipeline provided in the code.

---

## Contributing

Feel free to open issues, discuss improvements, or submit pull requests to enhance this classifier.

## Acknowledgments

Special thanks to the creators of the dataset and the Kaggle community for supporting machine learning initiatives.
