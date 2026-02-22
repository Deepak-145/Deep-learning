🔢 MNIST Digit Classification using MLP
📌 Overview

This project classifies handwritten digits (0–9) using a Multi-Layer Perceptron (MLP) neural network.

It was built during my Deep Learning learning phase to understand:

Image preprocessing
Flattening image data
Multi-class classification
Softmax activation

📊 Dataset

Dataset: MNIST Handwritten Digits
60,000 training images
10,000 testing images
Image size: 28 × 28 pixels
10 output classes (digits 0–9)

🧠 Model Architecture
model = Sequential()

model.add(Input(shape=(28,28)))
model.add(Flatten())
model.add(Dense(256, activation='relu'))
model.add(Dense(128, activation='relu'))
model.add(Dense(10, activation='softmax'))
Architecture Explanation:

Input: 28×28 grayscale image
Flatten: Converts image into 1D vector
Hidden Layers: 256 and 128 neurons (ReLU)
Output Layer: 10 neurons (Softmax for multi-class classification)

⚙️ Training Details

Optimizer: Adam
Loss Function: Categorical Crossentropy
Activation: ReLU (hidden), Softmax (output)

🎯 Goal of This Project

Understand image classification basics
Learn multi-class neural network setup
Practice model evaluation and accuracy tracking
