# Satellite-image-classification
This project focuses on classifying satellite images into different categories using a deep Convolutional Neural Network (CNN). The model is trained on a dataset comprising images from four classes: **Cloudy**, **Desert**, **Green Area**, and **Water**.
## 📂 Dataset

The dataset is sourced from Kaggle:  
🔗 [Satellite Image Classification Dataset](https://www.kaggle.com/datasets/mahmoudreda55/satellite-image-classification)

It includes satellite images organized into the following folders:
- `/cloudy`
- `/desert`
- `/green_area`
- `/water`

---

## Model Architecture

The core of this project is a Convolutional Neural Network (CNN) built using TensorFlow and Keras. The model includes:
- Multiple convolutional and max-pooling layers
- Dropout layers for regularization
- Flatten and Dense layers for classification
- Softmax output activation for multi-class classification

---

##  Setup Instructions

1. Clone this repository.
2. Make sure you have Python 3.7+ installed.
3. Install required packages using the list below.
4. Configure Kaggle credentials to access the dataset:
   ```bash
   mkdir -p ~/.kaggle
   cp kaggle.json ~/.kaggle/
   chmod 600 ~/.kaggle/kaggle.json
