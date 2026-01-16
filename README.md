# Potato Leaf Disease Prediction Using Convolutional Neural Networks

## Project Description
This project implements a deep learning–based image classification system to identify diseases in potato leaves. A Convolutional Neural Network (CNN) is trained to classify leaf images into three disease categories.

## Diseases Classified
- Potato Late Blight
- Potato Early Blight
- Potato Bacterial Wilt

## Objective
To automate the detection of potato leaf diseases using image processing and deep learning techniques, enabling early diagnosis and reducing crop loss.

## Dataset
The dataset consists of potato leaf images organized into three folders:
- `Potato_Late_Blight`
- `Potato_Early_Blight`
- `Potato_Bacterial_Wilt`

Each folder contains images corresponding to one disease class.

> Note: The dataset is not included in this repository due to size constraints.  
> Download the dataset and place it inside the `data/` directory before running the notebook.

## Methodology
1. Image loading and preprocessing using OpenCV and PIL
2. Image resizing and normalization
3. Label encoding and train-test split
4. CNN model creation using Keras
5. Model training with Early Stopping
6. Model evaluation and prediction

## Model Used
- Convolutional Neural Network (CNN)
  - Convolution layers
  - MaxPooling layers
  - Dropout for regularization
  - Dense layers with Softmax activation

## Tools & Libraries
- Python
- Google Colab
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- PIL

## How to Run
1. Clone the repository
2. Place the dataset inside the `data/` folder
3. Open `Potato_Leaf_Disease_Prediction.ipynb` in Google Colab or Jupyter Notebook
4. Run all cells sequentially

## Results
The trained CNN model successfully classifies potato leaf images into three disease categories with good accuracy.

## Future Scope
- Add more potato diseases
- Improve accuracy with data augmentation
- Deploy as a web or mobile application

## Author
Sanskriti Singh
