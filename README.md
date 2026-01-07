# MNIST ML AI Project

This project is a **from-scratch neural network implementation using NumPy** to classify handwritten digits from the MNIST dataset.

No machine learning frameworks like TensorFlow or PyTorch are used.  
The goal is to understand how neural networks work internally.

---

## 📌 Project Overview

- Classifies digits (0–9) from 28×28 pixel images
- Implements forward propagation and backpropagation manually
- Uses gradient descent for training
- Visualizes predictions using Matplotlib

---

## 🧠 Model Architecture

- Input Layer: 784 neurons (28×28 pixels)
- Hidden Layer: 10 neurons (ReLU activation)
- Output Layer: 10 neurons (Softmax)

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib

---

## 📊 Dataset

- MNIST handwritten digits dataset
- Pixel values normalized to range [0, 1]
- Data shuffled and split into training and development sets

This project uses the MNIST handwritten digits dataset.

The dataset is **not included** in this repository.  
If the dataset is not found locally, the code will automatically download MNIST from **OpenML** and store it in the `data/` directory.

This ensures the project can be run on any system without manual dataset setup.

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Nihal-VS/MNIST_ML_AI_project.git
   
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib
   
3. Run the Python script:
   ```bash
   python mnist_nn.py

---

## 📈 Results

- Achieves ~85% accuracy on the development set
- Displays predicted digit along with the actual label

---

## 🎯 Learning Outcomes

- Understanding neural networks from scratch
- Hands-on experience with backpropagation
- Improved intuition of matrix operations in ML

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
