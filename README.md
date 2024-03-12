# Image Classification using CNN

This project focuses on classifying small images from the CIFAR-10 dataset using Convolutional Neural Networks (CNNs) with TensorFlow's Keras datasets. The CIFAR-10 dataset contains 60,000 32x32 color images across 10 classes, making it a suitable dataset for image classification tasks.

## Approach

We leverage CNNs for this classification task due to their ability to automatically learn hierarchical features from image data. CNNs are particularly effective for image classification tasks, offering superior accuracy compared to traditional Artificial Neural Networks (ANNs).

## Implementation

1. **Data Loading and Analysis**: We load the CIFAR-10 dataset and analyze its structure. We also visualize sample images along with their corresponding labels.

2. **Data Preprocessing**: Pixel values of the images are normalized to range between 0 and 1 for better model training.

3. **ANN**: We start with building an Artificial Neural Network (ANN) for image classification and evaluate its performance.

4. **CNN**: Next, we build a CNN model for image classification and evaluate its performance. CNNs achieve higher accuracy compared to ANNs for this task.

5. **Conclusion**: CNNs offer exceptional accuracy and efficiency for image classification tasks, making them a powerful tool for such applications.

## Results

- ANN Accuracy: Around 50% after 5 epochs.
- CNN Accuracy: Approximately 75% after 5 epochs, showcasing the superiority of CNNs for image classification tasks.
