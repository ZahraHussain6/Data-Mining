# X-Ray Fracture Detection Project

## Introduction

The X-Ray Fracture Detection Project is a deep learning project aimed at automatically detecting bone fractures in X-ray images. The project utilizes convolutional neural networks (CNNs), multi-layer perceptrons (MLPs), vision transformers, and transfer learning techniques to analyze X-ray images and classify them as either containing a fracture or not.

## Features

- Automatic detection of bone fractures in X-ray images using various deep learning models.
- Efficient processing of large datasets using TensorFlow and Keras.
- Integration of data augmentation techniques to improve model robustness.
- Visualization of model predictions and evaluation metrics.

## Models Used

### Convolutional Neural Networks (CNNs)
- CNNs are used as the primary architecture for image classification in this project. Various CNN architectures, including VGG and EfficientNetB0, are explored and compared for their performance in fracture detection.

### Multi-Layer Perceptrons (MLPs)
- MLPs are used as baseline models for comparison against CNNs. These models consist of fully-connected layers and are trained on flattened image pixels to classify X-ray images.

### Vision Transformers
- Vision Transformers (ViTs) are employed to investigate their effectiveness in fracture detection. ViTs process image patches using self-attention mechanisms, offering an alternative approach to CNN-based architectures.

### Transfer Learning
- Transfer learning techniques are utilized to fine-tune pre-trained CNN models, such as EfficientNet, on the X-ray fracture detection task. By leveraging features learned from large-scale datasets like ImageNet, transfer learning helps improve model performance on the target task with limited data.

## DataSet

(https://www.kaggle.com/datasets/vuppalaadithyasairam/bone-fracture-detection-using-xrays/data)
### Contributors: 
Fayez Ali

Jazib Ali
