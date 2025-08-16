# Neural Network from Scratch (NumPy)  

A 3-layer feedforward neural network implemented entirely with **NumPy**, trained to classify handwritten digits from the **MNIST dataset**. Both the forward and backward passes, as well as optimization algorithms, were coded manually — no deep learning frameworks used.  

## ✨ Features  
- **3-layer architecture**: Input → Hidden (ReLU) → Output (Softmax)  
- **Manual implementation** of forward propagation & backpropagation  
- **Loss function**: Categorical Cross-Entropy  
- **Optimization algorithms implemented from scratch**:  
  - Mini-batch Gradient Descent  
  - Adam Optimizer  
- **Training pipeline** with batching, accuracy tracking, and validation set  
- Achieved **91.2% validation accuracy** on MNIST  

## 📊 Results
- Validation Accuracy: 91.2%
- Architecture: [784 → 128 (ReLU) → 10 (Softmax)]
- Optimizer: Adam / Mini-batch Gradient Descent
