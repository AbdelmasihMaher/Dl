# Dl
# Handwritten Digit Recognition using CNN (MNIST)

## Project Description

This project implements a Convolutional Neural Network (CNN) for handwritten digit recognition using the MNIST dataset.
The model classifies handwritten digits from 0 to 9 with high accuracy.

---

## Dataset

MNIST Dataset
Dataset Source: TensorFlow / Keras built-in dataset

* Training Images: 60,000
* Testing Images: 10,000
* Image Size: 28 × 28 grayscale images

---

## Data Preprocessing

The following preprocessing steps were applied:

* Image normalization
* Reshaping images for CNN input
* One Hot Encoding for labels

---

## Model Architecture

The CNN model contains:

* Convolutional Layers (Conv2D)
* MaxPooling Layers
* Batch Normalization
* Flatten Layer
* Dense Layer
* Dropout Layer
* Softmax Output Layer

---

## Experiments

Two experiments were performed using different optimizers:

| Model   | Optimizer |
| ------- | --------- |
| Model A | Adam      |
| Model B | SGD       |

---

## Results

| Model          | Accuracy        | Loss        |
| -------------- | --------------- | ----------- |
| Model A (Adam) | Higher Accuracy | Lower Loss  |
| Model B (SGD)  | Lower Accuracy  | Higher Loss |

The Adam optimizer achieved faster convergence and better overall performance compared to SGD.

---

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib

---

## How to Run

Install required libraries:

```bash id="e4xq7m"
pip install tensorflow numpy matplotlib
```

Run the project:

```bash id="w8dv0j"
python main.py
```

---

## Output

The project generates:

* Training vs Validation Accuracy curves
* Training vs Validation Loss curves
* Model comparison table
* Saved trained CNN model
