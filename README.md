# Pneumonia Detection using CNN

## Project Overview

This project is a Deep Learning based Pneumonia Detection system using a
Convolutional Neural Network (CNN).

The model classifies chest X-ray images into two categories:

-   NORMAL
-   PNEUMONIA

The CNN model learns image patterns from X-ray images and predicts
whether pneumonia is present.

------------------------------------------------------------------------

## Project Structure

    pneumonia-cnn/

    ├── pneumonia_cnn.ipynb
    ├── pneumonia_model.keras
    ├── accuracy_graph
    ├── confusion_matrix
    ├── requirements.txt
    └── README.md

------------------------------------------------------------------------

## Technologies Used

-   Python
-   TensorFlow
-   Keras
-   CNN (Convolutional Neural Network)
-   NumPy
-   Pandas
-   Matplotlib
-   Seaborn
-   Scikit-learn
-   Pillow

------------------------------------------------------------------------

## Dataset

Dataset: Chest X-Ray Pneumonia Dataset

Classes:

1.  NORMAL
2.  PNEUMONIA

The dataset contains training, validation, and testing images.

------------------------------------------------------------------------

## Model Architecture

The CNN model contains:

-   Conv2D layers for feature extraction
-   MaxPooling layers
-   Flatten layer
-   Dense layers
-   Dropout layer
-   Sigmoid output layer

Model Type: Binary Image Classification

Optimizer: Adam

Loss Function: Binary Crossentropy

------------------------------------------------------------------------

## Data Preprocessing

Images are processed using:

-   Image resizing (128x128)
-   Pixel normalization
-   Data augmentation

------------------------------------------------------------------------

## Model Training

The model is trained using:

-   Training dataset
-   Validation dataset

Performance is measured using:

-   Accuracy
-   Loss
-   Validation accuracy

Generated graphs:

-   Accuracy graph
-   Loss graph
-   Confusion matrix

------------------------------------------------------------------------

## Model Evaluation

Evaluation metrics:

-   Accuracy Score
-   Classification Report
-   Confusion Matrix

------------------------------------------------------------------------

## Prediction

The trained model predicts:

    NORMAL
    or
    PNEUMONIA

Example:

    Prediction: PNEUMONIA
    Confidence: 95%

------------------------------------------------------------------------

## Installation

Install required libraries:

``` bash
pip install tensorflow numpy pandas matplotlib seaborn scikit-learn pillow
```

------------------------------------------------------------------------

## How to Run

1.  Open the notebook:

```{=html}
<!-- -->
```
    pneumonia_cnn.ipynb

2.  Install dependencies.

3.  Run all cells.

------------------------------------------------------------------------

## Saving Model

The trained model is saved as:

    pneumonia_model.keras

Load model:

``` python
from tensorflow.keras.models import load_model

model = load_model("pneumonia_model.keras")
```

------------------------------------------------------------------------

## Future Improvements

-   Use Transfer Learning models like VGG16, ResNet50, EfficientNet
-   Deploy using Flask or Streamlit
-   Improve model accuracy

------------------------------------------------------------------------

## Author

**Barsarani Khuntia**

Deep Learning Project\
Pneumonia Detection using CNN
