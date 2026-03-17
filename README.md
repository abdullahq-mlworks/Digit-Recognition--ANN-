## 🧠 Digit Recognition (ANN - MNIST)
Handwritten digit recognition is a fundamental problem in computer vision.
This project uses an Artificial Neural Network (ANN) to classify digits (0–9) from the MNIST dataset.

---

## 🔎 Overview
- Objective: Predict handwritten digits from image data.
- Dataset: MNIST (60,000 training images, 10,000 testing images).
- Workflow:
    1. Data Loading (MNIST dataset from Keras).
    2. Data Preprocessing (Normalization + One-Hot Encoding).
    3. Model Building (ANN using Keras Sequential API).
    4. Training with validation split.
    5. Evaluation using Accuracy & Loss.
    6. Visualization of performance graphs.

---

## 📂 Project Structure
Digit-Recognition/
- Digit Recognition.ipynb # Jupyter Notebook
- requirements.txt # Dependencies
- README.md # Project Documentation

---

## ⚙️ Installation
Clone the repository and install dependencies:
git clone https://github.com/abdullahq-mlworks/Digit-Recognition--ANN-.git
cd Digit-Recognition
pip install -r requirements.txt

---

## 🧾 Dataset
- Type: Grayscale images (28×28 pixels)
- Classes: 10 (Digits 0–9)
- Source: Keras MNIST dataset

---

## 🤖 Model
- Algorithm: Artificial Neural Network (ANN)
- Architecture:
    1. Flatten Layer (28×28 → 784)
    2. Dense Layer (128 neurons, ReLU)
    3. Dense Layer (64 neurons, ReLU)
    4. Output Layer (10 neurons, Softmax)
- Compilation:
    - Optimizer: Adam
    - Loss: Categorical Crossentropy
    - Metric: Accuracy

---

## 📊 Results
- High accuracy achieved on test data (~97–98%).
- Training and validation curves show good convergence.

---

## 📈 Output
- Accuracy Graph (Training vs Validation)
- Loss Graph (Training vs Validation)
- Predicted digit probabilities

---

## 🚀 Future Work
- Implement CNN for improved performance
- Hyperparameter tuning
- Model deployment (Streamlit / Flask)
- Real-time digit recognition

---