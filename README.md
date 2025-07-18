# Brain Tumor Detection Using CNN

A deep learning project to detect brain tumors from MRI images using Convolutional Neural Networks (CNN).

## 📂 Dataset

- Source: [Kaggle Brain MRI Images for Brain Tumor Detection](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection)
- Classes:
  - `yes/` – MRI images with brain tumor
  - `no/` – MRI images without brain tumor

## 🧠 Model Architecture

- 2D Convolutional Layers
- Max Pooling
- Batch Normalization
- Dropout for regularization
- Fully connected Dense layers
- Output: Softmax (2-class)

## 🔍 Key Features

- Input image resizing to 128x128
- OneHot encoding of labels (0: Tumor, 1: No Tumor)
- Accuracy and loss visualization
- Model evaluation and prediction demo with confidence

## 🖼️ Sample Prediction Output

```python
Its a Tumor
92.5% Confidence
