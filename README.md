[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rileybarka/Lab-7-MNIST-CNN/blob/main/notebooks/Lab7.ipynb)

# Lab 7: Handwritten Digit Classification with CNN on MNIST

This lab explores image classification using a convolutional neural network (CNN) trained on the MNIST handwritten digits dataset.

---

## Dataset Used

| Dataset | Description |
|---------|-------------|
| **MNIST Handwritten Digits** | A collection of 70,000 labeled grayscale images of handwritten digits (0-9), used for supervised learning in image classification. |

---

## Objectives

- Define the classification task: recognize digits 0 through 9  
- Import and visualize MNIST image data  
- Preprocess and prepare data for modeling (normalization, reshaping)  
- Construct a convolutional neural network using Keras  
- Train the CNN on the training dataset  
- Evaluate performance on training and test sets  
- Analyze accuracy and loss trends during training  

---

## Methodology

1. Load the MNIST dataset via Keras or alternative source  
2. Visualize sample images to understand data characteristics  
3. Normalize pixel values and reshape data for CNN input  
4. Build CNN architecture with convolutional, pooling, and dense layers  
5. Compile and train the model with appropriate loss function and optimizer  
6. Evaluate the model and visualize training metrics  

---

## Setup Instructions

### Open in Google Colab  
Click the badge above.

### Run Locally

```bash
git clone https://github.com/rileybarka/Lab-7-MNIST-CNN.git
cd Lab-7-MNIST-CNN/notebooks
jupyter notebook Lab7.ipynb
