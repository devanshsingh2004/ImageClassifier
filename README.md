# CIFAR-10 Image Classification from Scratch

## Overview
This project implements an image classification model from scratch using NumPy to classify images from three CIFAR-10 classes (3, 5, and 7). It covers:
- Forward and backward propagation
- Gradient descent optimization
- Manual training loop

## Results
- **Training Accuracy**: 86.36%
- **Test Accuracy**: 55.22%
- **Classes**: 3, 5, 7
- **Confusion Matrix and Classification Report** included.

## Run Instructions (Google Colab)
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the notebook `Q1_ImageClassifier.ipynb` to Colab.
3. Install dependencies in the first code cell:
   ```bash
   !pip install numpy matplotlib scikit-learn
   ```
4. Run all cells to:

Train the model

View training loss and accuracy plots

Display the confusion matrix and classification report

## 📸 Sample Input/Output
### Input: CIFAR-10 images (pre-processed) belonging to classes:

3: Cat

5: Dog

7: Horse

### Preprocessing:

Flattened 32x32 RGB images into 1D arrays

Normalized pixel values to the [0, 1] range

### Output:

Training loss and accuracy plots

Confusion matrix

Classification report
