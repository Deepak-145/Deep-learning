🎓 Admission Prediction using MLP
📌 Overview

This project predicts the probability of admission into a graduate program using a Multi-Layer Perceptron (MLP) neural network.
It was built as part of my Deep Learning learning phase.

🧠 Model Architecture
model = Sequential()

model.add(Input(shape=(7,)))
model.add(Dense(64, activation='relu'))
model.add(Dense(32, activation='relu'))
model.add(Dense(1, activation='linear'))

2 Hidden Layers (ReLU)

Output Layer (Linear – Regression)

⚙️ Training Details

Epochs: 100
Optimizer: Adam
Loss Function: MSE
Evaluation Metric: R² Score

📈 Result

Final R² Score: 0.77
Model explains ~77% variance in admission probability.
Stable training and validation performance.

📊 Dataset

Source: Kaggle

