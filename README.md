# Handwritten Digit Recognition

A machine learning project comparing **Logistic Regression (One-vs-All)** and **Convolutional Neural Network (CNN)** for recognizing handwritten digits (0-9) from 28×28 grayscale images.

## Dataset

**MNIST** - Images organized in subfolders `0/` through `9/`

## Project Structure

```
├── Handwritten_Digit_Recognition.ipynb   # Main notebook (click to view)
├── train/                                # Training data folder
│   ├── 0/                                 # Images of digit 0
│   ├── 1/                                 # Images of digit 1
│   └── ...                                # Digits 2-9
├── test/                                  # Test images folder
├── logistic_models.npy                    # Saved logistic regression weights
├── cnn_model.h5                           # Saved CNN model
└── scaler.pkl                             # Saved StandardScaler
```

## Models Implemented

| Model | Approach |
|-------|----------|
| Logistic Regression | 10 binary classifiers (One-vs-All), mini-batch gradient descent |
| CNN | VGG-like architecture with 3 convolutional blocks |

## View Notebook

**[Open Handwritten_Digit_Recognition.ipynb](./Handwritten_Digit_Recognition.ipynb)**

## Requirements

```
tensorflow
numpy
scikit-learn
matplotlib
seaborn
pillow
```
