# 🧠 Fashion MNIST Image Classification using TensorFlow

This project demonstrates how to use a basic neural network in TensorFlow and Keras to classify images of clothing using the Fashion MNIST dataset.

## 📚 Dataset
- 28x28 grayscale images
- 60,000 training, 10,000 test samples
- 10 fashion categories

## 🧠 Model Architecture
- Flatten input layer
- Dense layer with 128 neurons (ReLU)
- Output layer with 10 neurons (logits)
- Optimizer: Adam
- Loss: Sparse Categorical Crossentropy

## 🎯 Accuracy
Achieved **~88-92% accuracy** on the test dataset.

## 📊 Visualization
- Image + predicted label
- Bar chart of class probabilities

## ▶️ How to Run
```bash
git clone https://github.com/your-username/fashion-mnist-tensorflow.git
cd fashion-mnist-tensorflow
jupyter notebook image_classification_tensorflow.ipynb
