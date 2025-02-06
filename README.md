# Image Classification Using Cifar 10 Dataset

## Overview
This project implements an image classification model using the CIFAR-10 dataset. The model is built using **Convolutional Neural Networks (CNNs)** in TensorFlow/Keras to classify images into 10 different categories.

## Dataset
CIFAR-10 is a well-known dataset containing **60,000 images** (32x32 pixels, RGB) divided into 10 classes:
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/SPPramod/Image-Classify.git
   cd Image-Classify
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the training script:
   ```bash
   python train.py
   ```

## Limitations
- Low-resolution images (32x32) limit feature extraction.
- Limited to 10 predefined classes.
- Not suitable for advanced image recognition tasks (e.g., object detection, segmentation).

## Future Improvements
- Train on larger, more diverse datasets like ImageNet.
- Experiment with deeper architectures (ResNet, EfficientNet).
- Implement data augmentation techniques to improve generalization.

## Contact

For any inquiries or feedback, please contact:

- **Sathya Pushana Pramod**: [pushanapramod@gmail.com](mailto:pushanapramod@gmail.com)
- **GitHub**: [SPPramod](https://github.com/SPPramod)

