# 🔎Convolutional Neural Network for Lung Segmentation
[![pt-br](https://img.shields.io/badge/lang-pt--br-green.svg)](https://github.com/Jhones257/CNNPULMAO/blob/main/README.pt-br.md)


Author: [Jhones Soares](https://github.com/Jhones257)

# 👩‍💻Convolutional Neural Network
A Convolutional Neural Network (CNN) is a type of artificial neural network that is particularly effective for processing data with a grid-like structure, such as images. CNN architecture is inspired by the organization of the animal visual cortex and is composed of convolutional layers that apply filters to extract important features from the data, followed by pooling layers that reduce data dimensionality. These networks can be applied to computer vision tasks such as image classification, object detection, and semantic segmentation.

# Advantages:
- Ability to capture local patterns in data
- Reduction in complexity
- Ability to learn feature hierarchies

# 🖥CNN Implementation

This algorithm works in three main stages:
 - 1 Data preparation, standardizing image size and converting all images to grayscale.
 - 2 Definition of metrics for model evaluation. In this case, I am using DICE, IoU, and F1 Score to assess model performance.
 - 3 Model construction, consisting of 9 convolutional layers using the sigmoid activation function.

# 👩‍💻About the Project
In this project, I aim to apply a variation of CNN architecture for lung area segmentation, which in the future could assist in medical diagnoses, such as COVID-19 detection through image analysis. The chosen variation is U-net, as after several tests, it showed the best performance for the task.

Key functionalities include:
  - ✨Lung area segmentation.
  - ✨Visualization of the segmented area in the network's output.
  - ✨Metrics to validate segmentation accuracy.

# Example outputs and obtained results:

The model achieved the following results in training and testing:

Training:
 Accuracy: 99.02%
 Dice: 97.46%
 F1: 42.80%
 IoU: 99.22%

Testing:
 Accuracy: 97.83%
 Dice: 94.98%
 F1: 44.77%
 IoU: 98.65%

![output da rede neural](https://github.com/Jhones257/CNNPULMAO/blob/main/OutputRede.png)

![Gráficos dos resultados](https://github.com/Jhones257/CNNPULMAO/blob/main/graficos_rede.png)

