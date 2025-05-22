# Image-Classification-on-MNIST-Using-Deep-Learning-and-SVM
Description:
This project focuses on classifying handwritten digits from the MNIST dataset using both Convolutional Neural Networks (CNNs) and traditional machine learning models like Support Vector Machine (SVM). It evaluates and compares their performance in terms of accuracy and training time.

Key Components:

Dataset: MNIST dataset (28×28 grayscale images of digits 0–9).

Data Preprocessing:

Normalizing pixel values.

Reshaping images for CNN input.

Splitting data into training, validation, and test sets.

Models Implemented:

CNN: A custom architecture built using multiple Conv2D and MaxPooling2D layers followed by dense layers.

ANN: A simple fully connected neural network.

SVM: A traditional machine learning model trained on flattened image data for comparison.

Evaluation:

Accuracy, training time per epoch, and classification reports are used for model comparison.

Visualization of sample predictions and metrics.

Objective:
To explore how different CNN configurations compare to basic neural networks and SVMs in solving digit classification problems.

